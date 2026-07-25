---
title: Final Gradebook
---

<style>
:root {
    --gb-accent: #a51c30;
    --gb-badge-bg: rgba(165, 28, 48, 0.1);
    --gb-badge-border: rgba(165, 28, 48, 0.3);
}

@media (prefers-color-scheme: dark) {
    :root {
        --gb-accent: #ff6b81;
        --gb-badge-bg: rgba(255, 107, 129, 0.15);
        --gb-badge-border: rgba(255, 107, 129, 0.35);
    }
}

html[data-theme="dark"] :root,
html[data-bs-theme="dark"] :root,
body.dark :root,
body.theme-dark :root {
    --gb-accent: #ff6b81;
    --gb-badge-bg: rgba(255, 107, 129, 0.15);
    --gb-badge-border: rgba(255, 107, 129, 0.35);
}

.gradebook-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 4rem 2rem;
}
.gradebook-icon {
    font-size: 4rem;
    color: var(--gb-accent);
    margin-bottom: 1.5rem;
    opacity: 0.9;
}
.gradebook-title {
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 0.75rem;
}
.gradebook-subtitle {
    font-size: 1.1rem;
    opacity: 0.75;
    max-width: 480px;
    line-height: 1.6;
    margin-bottom: 2rem;
}
.gradebook-badge {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: var(--gb-badge-bg);
    border: 1px solid var(--gb-badge-border);
    color: var(--gb-accent);
    border-radius: 30px;
    padding: 0.5rem 1.25rem;
    font-weight: 600;
    font-size: 0.95rem;
}
</style>

<div class="gradebook-container">
    <div class="gradebook-icon">
        <i class="fas fa-chart-bar"></i>
    </div>
    <div class="gradebook-title">Final Gradebook</div>
    <div class="gradebook-subtitle">
        Your final gradebook will be shared with you at the end of the course once all problem sets and assessments have been reviewed.
    </div>
    <div class="gradebook-badge">
        <i class="fas fa-clock"></i> Available at the End of the Course
    </div>
</div>
