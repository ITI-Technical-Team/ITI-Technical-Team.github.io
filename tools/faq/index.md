---
title: Frequently Asked Questions
permalink: /tools/faq/
---

# Frequently Asked Questions (FAQ)

Find step-by-step guides for getting started with ITI CS50, setting up your environment, and submitting your assignments.

<style>
:root {
    --faq-badge-bg: rgba(165, 28, 48, 0.1);
    --faq-badge-color: #a51c30;
    --faq-icon-color: #a51c30;
}

@media (prefers-color-scheme: dark) {
    :root {
        --faq-badge-bg: rgba(255, 107, 129, 0.15);
        --faq-badge-color: #ff6b81;
        --faq-icon-color: #ff6b81;
    }
}

html[data-theme="dark"] :root,
html[data-bs-theme="dark"] :root,
body.dark :root,
body.theme-dark :root {
    --faq-badge-bg: rgba(255, 107, 129, 0.15);
    --faq-badge-color: #ff6b81;
    --faq-icon-color: #ff6b81;
}

.faq-section {
    margin-top: 2rem;
    margin-bottom: 3rem;
}

.faq-item {
    background: var(--card-bg, rgba(var(--bs-body-color-rgb), 0.02));
    border: 1px solid var(--card-border, var(--bs-border-color));
    box-shadow: var(--card-shadow, 0 4px 12px rgba(0, 0, 0, 0.03));
    border-radius: 10px;
    margin-bottom: 1.25rem;
    overflow: hidden;
    transition: all 0.25s ease;
}

.faq-item summary {
    padding: 1.25rem 1.5rem;
    font-size: 1.15rem;
    font-weight: 700;
    cursor: pointer;
    color: var(--bs-heading-color);
    display: flex;
    align-items: center;
    justify-content: space-between;
    list-style: none;
    user-select: none;
}

.faq-item summary::-webkit-details-marker {
    display: none;
}

.faq-item summary::after {
    content: '\f078';
    font-family: 'Font Awesome 5 Free';
    font-weight: 900;
    font-size: 0.9rem;
    opacity: 0.6;
    transition: transform 0.2s ease;
    margin-left: 1rem;
}

.faq-item[open] summary::after {
    transform: rotate(180deg);
}

.faq-item summary:hover {
    background: rgba(var(--bs-body-color-rgb), 0.04);
}

.faq-content {
    padding: 0 1.5rem 1.5rem 1.5rem;
    border-top: 1px solid rgba(var(--bs-body-color-rgb), 0.08);
    line-height: 1.6;
}

.faq-step-list {
    margin-top: 1rem;
    padding-left: 1.25rem;
}

.faq-step-list li {
    margin-bottom: 0.75rem;
}

.faq-badge {
    display: inline-block;
    padding: 0.3rem 0.75rem;
    font-size: 0.85rem;
    font-weight: 700;
    border-radius: 20px;
    background: var(--faq-badge-bg);
    color: var(--faq-badge-color);
    margin-bottom: 0.75rem;
}

.faq-tip-box {
    background: rgba(52, 152, 219, 0.08);
    border-left: 4px solid #3498db;
    padding: 1rem 1.25rem;
    border-radius: 4px;
    margin-top: 1rem;
    font-size: 0.95rem;
}

.faq-tip-box i {
    color: #3498db;
    margin-right: 0.5rem;
}
</style>

<div class="faq-section">

    <!-- Question 1 -->
    <details class="faq-item" open>
        <summary>
            <span><i class="fab fa-github" style="margin-right: 0.75rem; color: var(--faq-icon-color);"></i> How to Create a GitHub Account</span>
        </summary>
        <div class="faq-content">
            <div class="faq-badge">Step 1: Account Setup</div>
            <p>GitHub is required for logging into <code>cs50.dev</code>, submitting your coursework via <code>submit50</code>, and viewing grade checks.</p>
            <ol class="faq-step-list">
                <li>Go to <a href="https://github.com/signup" target="_blank" rel="noopener">github.com/signup</a>.</li>
                <li>Enter your primary email address and create a strong password.</li>
                <li>Choose a professional username (e.g., <code>alex-smith</code> or <code>john-doe</code>).</li>
                <li>Verify your account via the code sent to your email.</li>
                <li>Complete the quick account registration puzzle.</li>
            </ol>
            <div class="faq-tip-box">
                <i class="fas fa-info-circle"></i> <strong>Tip:</strong> Keep your GitHub credentials handy! You will use this account to log into all CS50 learning tools.
            </div>
        </div>
    </details>

    <!-- Question 2 -->
    <details class="faq-item">
        <summary>
            <span><i class="fas fa-envelope-open-text" style="margin-right: 0.75rem; color: var(--faq-icon-color);"></i> How to Join the Course & Accept Invitations</span>
        </summary>
        <div class="faq-content">
            <div class="faq-badge">Course Registration</div>
            <p>Courses and submissions are managed via <a href="https://submit.cs50.io" target="_blank" rel="noopener">submit.cs50.io</a>. When starting a cohort, your ITI instructors will provide a course invitation link.</p>
            <ol class="faq-step-list">
                <li>Click the course invitation link provided by your ITI instructor (which links to <code>submit.cs50.io</code>).</li>
                <li>Sign in using your <strong>GitHub account</strong> when prompted.</li>
                <li>Authorize <code>submit50</code> to connect with your GitHub account.</li>
                <li>Click <strong>"Join Course"</strong> or <strong>"Accept Invitation"</strong> to complete your enrollment.</li>
                <li>Once enrolled, you can submit your coursework anytime directly from your terminal using <code>submit50</code>!</li>
            </ol>
        </div>
    </details>

    <!-- Question 3 -->
    <details class="faq-item">
        <summary>
            <span><i class="fas fa-terminal" style="margin-right: 0.75rem; color: var(--faq-icon-color);"></i> How to Log in to cs50.dev (VS Code in Browser vs Desktop)</span>
        </summary>
        <div class="faq-content">
            <div class="faq-badge">Development Environment</div>
            <p>CS50 provides a cloud-based Visual Studio Code workspace pre-configured with C++, HTML/CSS/JS tools, <code>check50</code>, and <code>submit50</code>.</p>

            <h4 style="margin-top: 1rem;">1. Logging in via Browser</h4>
            <ol class="faq-step-list">
                <li>Open your browser and navigate to <a href="https://cs50.dev" target="_blank" rel="noopener">cs50.dev</a>.</li>
                <li>Click the main <strong>"Log in with GitHub"</strong> button.</li>
                <li>Authorize CS50 to access your GitHub account. Your cloud IDE environment will launch automatically in the browser!</li>
            </ol>

            <div class="faq-tip-box">
                <i class="fas fa-caret-square-down"></i> <strong>Opening in VS Code Desktop:</strong><br>
                On the <a href="https://cs50.dev" target="_blank" rel="noopener">cs50.dev</a> login page, right next to the <strong>"Log in"</strong> button, you will see a small <strong>drop-down arrow button (▼)</strong>.<br>
                Clicking this drop-down arrow reveals an option: <strong>"Open in VS Code Desktop"</strong>. If you have VS Code installed locally on your computer, this opens your CS50 codespace directly inside your desktop editor!
            </div>
        </div>
    </details>

    <!-- Question 4 -->
    <details class="faq-item">
        <summary>
            <span><i class="fas fa-desktop" style="margin-right: 0.75rem; color: var(--faq-icon-color);"></i> How to Install VS Code Desktop</span>
        </summary>
        <div class="faq-content">
            <div class="faq-badge">Local Tools</div>
            <p>If you prefer working in VS Code on your local machine instead of the web browser, follow these steps to install VS Code Desktop:</p>
            <ol class="faq-step-list">
                <li>Visit the official website: <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">code.visualstudio.com</a>.</li>
                <li>Click <strong>Download</strong> for your operating system (Windows, macOS, or Linux).</li>
                <li>Run the installer executable and follow the setup wizard (accept agreement, select default settings).</li>
                <li>Open VS Code Desktop once installation completes.</li>
                <li>To connect to CS50: install the official <strong>GitHub Codespaces</strong> extension in VS Code, sign in with GitHub, and open your <code>cs50.dev</code> codespace!</li>
            </ol>
        </div>
    </details>

</div>
