---
title: Alex Aug 2026
---

# Welcome to ITI CS50
## Alexandria - August 2026 Cohort

This is the homepage for the custom **Alexandria August 2026** cohort. 

This program is a customized version of the curriculum tailored for your training track. It focuses on the fundamental concepts of computer science (Scratch and C++) and transitions into full Web Development (HTML, CSS, and JavaScript).

<style>
:root {
    --accent-color: #b3001e;
    --card-bg: rgba(var(--bs-body-color-rgb), 0.02);
    --card-border: var(--bs-border-color);
    --card-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
    --icon-red: #e74c3c;
    --icon-blue: #3498db;
}

/* Dark mode overrides (by preferences or selectors) */
@media (prefers-color-scheme: dark) {
    :root {
        --accent-color: #a51c30;
        --card-bg: rgba(255, 255, 255, 0.05);
        --card-border: rgba(255, 255, 255, 0.12);
        --card-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
        --icon-red: #c0392b;
        --icon-blue: #388bfd;
    }
}

html[data-theme="dark"] :root,
html[data-bs-theme="dark"] :root,
body.dark :root,
body.theme-dark :root {
    --accent-color: #a51c30;
    --card-bg: rgba(255, 255, 255, 0.05);
    --card-border: rgba(255, 255, 255, 0.12);
    --card-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
    --icon-red: #c0392b;
    --icon-blue: #388bfd;
}

.materials-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
}
.material-card {
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    box-shadow: var(--card-shadow);
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
    border-color: var(--accent-color);
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
    color: var(--accent-color);
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
    <a href="{{ '/courses/alex-aug-2026/slides/' | relative_url }}" class="material-card">
        <div class="card-icon" style="color: var(--icon-red);">
            <i class="far fa-file-pdf"></i>
        </div>
        <div class="card-title">Lecture PDFs</div>
        <div class="card-description">Download and review the presentation slides for your Alexandria lectures.</div>
        <div class="card-action">
            Browse Slides <i class="fas fa-arrow-right"></i>
        </div>
    </a>

    <a href="{{ '/courses/alex-aug-2026/tasks/' | relative_url }}" class="material-card">
        <div class="card-icon" style="color: var(--icon-blue);">
            <i class="fas fa-tasks"></i>
        </div>
        <div class="card-title">Lecture Tasks</div>
        <div class="card-description">Access your cohort's class tasks, practice exercises, and testing commands.</div>
        <div class="card-action">
            View Tasks <i class="fas fa-arrow-right"></i>
        </div>
    </a>
</div>
