---
title: Materials
permalink: /materials/
---

# Materials

Here you can access all the learning resources, slide presentations, practice tasks, and recordings for the course.

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
    <a href="{{ '/materials/slides/' | relative_url }}" class="material-card">
        <div class="card-icon text-danger">
            <i class="far fa-file-pdf"></i>
        </div>
        <div class="card-title">Lecture PDFs</div>
        <div class="card-description">Download and review the presentation slides for each lecture topic.</div>
        <div class="card-action">
            Browse Slides <i class="fas fa-arrow-right"></i>
        </div>
    </a>

    <a href="{{ '/materials/tasks/' | relative_url }}" class="material-card">
        <div class="card-icon text-info">
            <i class="fas fa-tasks"></i>
        </div>
        <div class="card-title">Lecture Tasks</div>
        <div class="card-description">Access class tasks, practice exercises, and automated test commands.</div>
        <div class="card-action">
            View Tasks <i class="fas fa-arrow-right"></i>
        </div>
    </a>

    <a href="{{ '/materials/recordings/' | relative_url }}" class="material-card">
        <div class="card-icon text-success">
            <i class="fas fa-video"></i>
        </div>
        <div class="card-title">Lecture Recordings</div>
        <div class="card-description">Watch video recordings of the live classroom lectures and reviews.</div>
        <div class="card-action">
            Watch Videos <i class="fas fa-arrow-right"></i>
        </div>
    </a>
</div>
