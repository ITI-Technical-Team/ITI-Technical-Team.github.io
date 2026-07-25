# Creating Custom Courses Guide

This guide explains how to set up a customized cohort course track (e.g., custom sidebar, syllabus, slides, and tasks) on this site using **Option 1: Liquid-Conditional Sidebars**.

This method allows a single branch codebase to host multiple customized courses. When a student visits a custom course sub-path, the sidebar menu dynamically updates to show only their selected topics and problem sets.

---

## Step 1: Create the Course Directory Workspace
Under `courses/`, create a new folder named after the cohort/course (e.g., `courses/alex-aug-2026/`).

Inside this folder, create three files:
1. `index.md`
2. `slides.md`
3. `tasks.md`

### 1. `index.md` (Landing Page)
Create the homepage for the cohort. Do NOT set a custom layout (like `layout: home`), as this will override the default theme and hide the sidebar. Use a modern card layout for navigation:

```markdown
---
title: Course Name (e.g., Alex Aug 2026)
---

# Welcome to ITI CS50
## Cohort Title

Introduce the custom track, cohort details, and explain what topics are covered. 

<style>
.materials-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
}
.material-card {
    background: rgba(var(--bs-body-color-rgb), 0.02);
    border: 1px solid var(--bs-border-color);
    border-radius: 8px;
    padding: 1.75rem;
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
    text-decoration: none !important;
    color: inherit !important;
    display: flex;
    flex-direction: column;
    height: 100%;
}
.material-card:hover {
    background: rgba(var(--bs-body-color-rgb), 0.05);
    border-color: var(--bs-primary);
    transform: translateY(-4px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.08);
}
.card-icon {
    font-size: 2.25rem;
    margin-bottom: 1rem;
}
.card-title {
    font-size: 1.25rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
    color: var(--bs-heading-color);
}
.card-description {
    font-size: 0.95rem;
    opacity: 0.8;
    line-height: 1.5;
    flex-grow: 1;
}
.card-action {
    margin-top: 1.5rem;
    font-weight: 600;
    font-size: 0.9rem;
    display: flex;
    align-items: center;
    color: var(--bs-primary);
    transition: gap 0.2s ease;
    gap: 4px;
}
.material-card:hover .card-action {
    gap: 8px;
}
.card-action i {
    transition: transform 0.2s ease;
}
.material-card:hover .card-action i {
    transform: translateX(4px);
}
</style>

<div class="materials-grid">
    <a href="{{ '/courses/<cohort-folder-name>/slides/' | relative_url }}" class="material-card">
        <div class="card-icon text-danger">
            <i class="far fa-file-pdf"></i>
        </div>
        <div class="card-title">Lecture PDFs</div>
        <div class="card-description">Download and review presentation slides.</div>
        <div class="card-action">
            Browse Slides <i class="fas fa-arrow-right"></i>
        </div>
    </a>

    <a href="{{ '/courses/<cohort-folder-name>/tasks/' | relative_url }}" class="material-card">
        <div class="card-icon text-info">
            <i class="fas fa-tasks"></i>
        </div>
        <div class="card-title">Lecture Tasks</div>
        <div class="card-description">Access cohort practice tasks and testing instructions.</div>
        <div class="card-action">
            View Tasks <i class="fas fa-arrow-right"></i>
        </div>
    </a>
</div>
```

### 2. `slides.md` (Custom Slides List)
Define the custom list of slides showing only the selected Days/topics. Ensure you configure the correct custom `permalink`.

```markdown
---
title: Lecture PDFs
permalink: /courses/<course-folder>/slides/
---

# Lecture PDFs

Here you can find the lecture slides and other materials for each day of the course.

<style>
/* Style declarations copied from materials/slides.md */
</style>

<div class="mt-4">
  <!-- Add track headers and resource-row items for the selected Days -->
  <h3 class="track-header">Programming Foundations</h3>
  <div class="resource-row track-foundations">
    <div class="d-flex align-items-center">
      <span class="badge bg-danger badge-day me-3">Day 1</span>
      <h5 class="day-title">Scratch I</h5>
    </div>
    <div>
      <a href="{{ '/assets/pdfs/Day1%20Scratch.pdf' | relative_url }}" class="btn btn-slides rounded-pill">
        <i class="far fa-file-pdf me-2"></i>Slides
      </a>
    </div>
  </div>
  <!-- Add other selected days... -->
</div>
```

### 3. `tasks.md` (Custom Tasks Index)
Define the custom list of lecture practice tasks. Ensure you configure the correct custom `permalink`.

```markdown
---
title: Lecture Tasks
permalink: /courses/<course-folder>/tasks/
---

# Lecture Tasks

Here you can find the lecture-specific tasks and practice exercises for each day of the course.

<style>
/* Style declarations copied from materials/tasks.md */
</style>

<div class="mt-4">
  <!-- Add track headers and resource-row collapsible items for the selected Days -->
  <h3 class="track-header">Programming Foundations</h3>
  <div class="resource-row track-foundations flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-1" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-danger badge-day me-3">Day 1</span>
        <h5 class="day-title">Scratch I</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">4 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-1">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-1/ask-user' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 1: Ask and Print
          </a>
        </li>
        <!-- Add other selected task list-items... -->
      </ul>
    </div>
  </div>
  <!-- Add other selected days... -->
</div>
```

---

## Step 2: Configure Dynamic Sidebar Navigation
In `_includes/nav.md`, wrap the custom sidebar structure in a Liquid `{% if page.url contains "/courses/<course-folder>/" %}` check:

```liquid
{% if page.url contains "/courses/alex-aug-2026/" %}
***
***
* ### [**Materials**]({{ "/courses/alex-aug-2026/" | relative_url }})

    - [**Lecture PDFs**]({{ "/courses/alex-aug-2026/slides/" | relative_url }})
    - [**Lecture Tasks**]({{ "/courses/alex-aug-2026/tasks/" | relative_url }})

***

* ### [**Problem Sets**]({{ "/courses/alex-aug-2026/" | relative_url }})

<!-- Add ONLY the <details> elements for the Problem Sets matching the chosen Days -->
<details markdown="1">
<summary><strong>Day 1 – Scratch I</strong></summary>
- [Playground]({{ "/pset/day-1/playground" | relative_url }})
...
</details>

***
* ### [**Tools**](/tools)
<!-- Include general course tools (FAQ, IDE, etc.) -->

{% else %}
  <!-- Original full-curriculum sidebar configuration -->
{% endif %}
```

---

## Step 3: Stage, Commit, and Deploy
Stage the modifications and push the branch to deploy:

```bash
git add _includes/nav.md courses/<course-folder>/
git commit -m "Add custom track for <course-name> cohort"
git push origin main
```

Verify that the GitHub Actions build passes successfully, and test the custom URLs to ensure the sidebar filters active content properly.
