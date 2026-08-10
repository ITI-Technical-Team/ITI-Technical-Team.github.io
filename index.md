---
title: false
---

<style>
:root {
    --accent-color: #b3001e;
    --accent-gradient: linear-gradient(90deg, #b3001e 0%, #e74c3c 100%);
    --card-bg: rgba(var(--bs-body-color-rgb), 0.02);
    --card-border: var(--bs-border-color);
    --card-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
    --track-red: #e74c3c;
    --track-green: #2ecc71;
    --track-blue: #3498db;
    --logo-filter: drop-shadow(0 4px 12px rgba(0,0,0,0.1));
}

/* Dark mode overrides (by preferences or selectors) */
@media (prefers-color-scheme: dark) {
    :root {
        --accent-color: #a51c30;
        --accent-gradient: linear-gradient(90deg, #a51c30 0%, #c0392b 100%);
        --card-bg: rgba(255, 255, 255, 0.05);
        --card-border: rgba(255, 255, 255, 0.12);
        --card-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
        --track-red: #c0392b;
        --track-green: #3fb950;
        --track-blue: #388bfd;
        --logo-filter: drop-shadow(0 4px 16px rgba(165, 28, 48, 0.2));
    }
}

html[data-theme="dark"] :root,
html[data-bs-theme="dark"] :root,
body.dark :root,
body.theme-dark :root {
    --accent-color: #a51c30;
    --accent-gradient: linear-gradient(90deg, #a51c30 0%, #c0392b 100%);
    --card-bg: rgba(255, 255, 255, 0.05);
    --card-border: rgba(255, 255, 255, 0.12);
    --card-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
    --track-red: #c0392b;
    --track-green: #3fb950;
    --track-blue: #388bfd;
    --logo-filter: drop-shadow(0 4px 16px rgba(165, 28, 48, 0.2));
}

.hero-section {
    padding: 3rem 1.5rem;
    text-align: center;
    background: linear-gradient(135deg, rgba(var(--bs-primary-rgb), 0.05) 0%, rgba(var(--bs-body-color-rgb), 0.02) 100%);
    border: 1px solid var(--card-border);
    border-radius: 12px;
    margin-bottom: 2.5rem;
}
.hero-title {
    font-size: 2.75rem;
    font-weight: 800;
    line-height: 1.2;
    margin-bottom: 1rem;
    background: var(--accent-gradient);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.hero-subtitle {
    font-size: 1.2rem;
    max-width: 700px;
    margin: 0 auto 2rem auto;
    opacity: 0.85;
    line-height: 1.6;
}
.hero-ctas {
    display: flex;
    justify-content: center;
    gap: 1rem;
}
.btn-hero-primary {
    background-color: var(--accent-color) !important;
    border-color: var(--accent-color) !important;
    color: #ffffff !important;
    padding: 0.75rem 1.5rem;
    font-weight: 600;
    border-radius: 30px;
    transition: all 0.2s ease;
    text-decoration: none !important;
}
.btn-hero-primary:hover {
    filter: brightness(0.95);
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(255, 77, 109, 0.2);
}
.btn-hero-secondary {
    background-color: transparent !important;
    border: 1.5px solid var(--card-border) !important;
    color: var(--bs-body-color) !important;
    padding: 0.75rem 1.5rem;
    font-weight: 600;
    border-radius: 30px;
    transition: all 0.2s ease;
    text-decoration: none !important;
}
.btn-hero-secondary:hover {
    background-color: rgba(var(--bs-body-color-rgb), 0.05) !important;
    border-color: var(--accent-color) !important;
    transform: translateY(-2px);
}

.stats-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.25rem;
    margin-bottom: 3rem;
}
.stat-card {
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    box-shadow: var(--card-shadow);
    border-radius: 8px;
    padding: 1.5rem;
    text-align: center;
}
.stat-number {
    font-size: 2.25rem;
    font-weight: 800;
    color: var(--accent-color);
    line-height: 1;
    margin-bottom: 0.5rem;
}
.stat-label {
    font-size: 0.95rem;
    font-weight: 600;
    opacity: 0.9;
    margin-bottom: 0.25rem;
}
.stat-desc {
    font-size: 0.85rem;
    opacity: 0.7;
}

.section-title {
    font-size: 1.75rem;
    font-weight: 700;
    margin-bottom: 1.5rem;
    text-align: center;
    position: relative;
    padding-bottom: 0.75rem;
    /* Override the CS50 theme's default h2 border-bottom */
    border-bottom: none !important;
}
.section-title::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 60px;
    height: 3px;
    background-color: var(--accent-color);
    border-radius: 2px;
}

.tracks-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-bottom: 3.5rem;
}
.track-card {
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    box-shadow: var(--card-shadow);
    border-radius: 8px;
    padding: 1.75rem;
    display: flex;
    flex-direction: column;
    height: 100%;
    transition: all 0.3s ease;
}
.track-card:hover {
    transform: translateY(-4px);
    background: rgba(var(--bs-body-color-rgb), 0.04);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.05);
}
.track-icon {
    font-size: 2rem;
    margin-bottom: 1rem;
}
.track-title {
    font-size: 1.2rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
    color: var(--bs-heading-color);
}
.track-desc {
    font-size: 0.9rem;
    opacity: 0.8;
    line-height: 1.5;
}

.overview-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 2rem;
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    box-shadow: var(--card-shadow);
    border-radius: 12px;
    padding: 2rem;
}
.overview-image {
    flex: 1 1 200px;
    display: flex;
    justify-content: center;
}
.overview-logo {
    max-width: 180px;
    height: auto;
    filter: var(--logo-filter);
    transition: transform 0.3s ease;
}
.overview-logo:hover {
    transform: scale(1.05);
}
.overview-content {
    flex: 2 1 400px;
}
.overview-content h3 {
    margin-top: 0;
    font-size: 1.35rem;
    font-weight: 700;
    margin-bottom: 0.75rem;
}
.overview-content p {
    font-size: 0.95rem;
    line-height: 1.6;
    opacity: 0.85;
    margin-bottom: 0;
}
</style>

<div class="hero-section">
    <h1 class="hero-title">Welcome to ITI CS50</h1>
    <p class="hero-subtitle">An introduction to the intellectual enterprises of computer science and the art of programming, customized for professional cohort tracks.</p>
    <div class="hero-ctas">
        <a href="{{ '/materials/' | relative_url }}" class="btn-hero-primary">Get Started</a>
        <a href="{{ '/materials/' | relative_url }}" class="btn-hero-secondary">Browse Materials</a>
    </div>
</div>

<div class="stats-grid">
    <div class="stat-card">
        <div class="stat-number">16</div>
        <div class="stat-label">Intensive Days</div>
        <div class="stat-desc">Structured syllabus tracks</div>
    </div>
    <div class="stat-card">
        <div class="stat-number">60+</div>
        <div class="stat-label">Practice Tasks</div>
        <div class="stat-desc">Hands-on coding exercises</div>
    </div>
    <div class="stat-card">
        <div class="stat-number">100%</div>
        <div class="stat-label">Automated Grading</div>
        <div class="stat-desc">Instant check50 feedback</div>
    </div>
</div>

<h2 class="section-title">What You Will Learn</h2>

<div class="tracks-grid">
    <div class="track-card" style="border-top: 4px solid var(--track-red);">
        <div class="track-icon" style="color: var(--track-red);"><i class="fas fa-shapes"></i></div>
        <div class="track-title">Scratch & Logic</div>
        <div class="track-desc">Master foundational concepts like variables, loops, conditional branches, functions, and events in a visual framework.</div>
    </div>
    <div class="track-card" style="border-top: 4px solid var(--track-green);">
        <div class="track-icon" style="color: var(--track-green);"><i class="fas fa-code"></i></div>
        <div class="track-title">Fundamentals of C++</div>
        <div class="track-desc">Build a strong code foundation with compilation, static variables, memory, sorting, search algorithms, and file structures.</div>
    </div>
    <div class="track-card" style="border-top: 4px solid var(--track-blue);">
        <div class="track-icon" style="color: var(--track-blue);"><i class="fas fa-globe"></i></div>
        <div class="track-title">Interactive Web Stack</div>
        <div class="track-desc">Design structured web layouts using HTML5, configure responsive stylesheets with CSS3, and manage user interactions with JavaScript DOM events.</div>
    </div>
</div>

<div class="overview-container">
    <div class="overview-image">
        <img src="{{ '/assets/images/iti-logo.png' | relative_url }}" alt="ITI Logo" class="overview-logo">
    </div>
    <div class="overview-content">
        <h3>About the Program</h3>
        <p>This program is a professional collaboration belonging to the Information Technology Institute (ITI). Administered and mentored by the Suez Canal Branch Technical Team, the course offers an intensive, customized curriculum adapted from Harvard University's renowned CS50x introduction to computer science. Our goal is to empower students with robust algorithmic thinking, code literacy, and software engineering foundations.</p>
    </div>
</div>