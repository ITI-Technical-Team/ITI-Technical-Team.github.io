---
title: Lecture Tasks
permalink: /courses/alex-aug-2026/tasks/
---

# Lecture Tasks

Here you can find the lecture-specific tasks and practice exercises for each day of the course.

<style>
.track-header {
    margin-top: 2rem;
    margin-bottom: 1.25rem;
    font-size: 1.25rem;
    font-weight: 600;
    border-bottom: 1px solid var(--bs-border-color);
    padding-bottom: 0.5rem;
}
.resource-row {
    display: flex;
    padding: 1rem 1.25rem;
    margin-bottom: 0.75rem;
    background-color: rgba(var(--bs-body-color-rgb), 0.02);
    border: 1px solid var(--bs-border-color);
    border-radius: 6px;
    transition: all 0.2s ease;
}
.resource-row:hover {
    background-color: rgba(var(--bs-body-color-rgb), 0.04);
    border-color: rgba(var(--bs-body-color-rgb), 0.15);
}
.track-foundations {
    border-left: 4px solid #e74c3c;
}
.track-web {
    border-left: 4px solid #3498db;
}
.day-title {
    margin: 0 !important;
    padding: 0 !important;
    font-weight: 600;
    font-size: 1.1rem;
    line-height: 1.2 !important;
}
.badge-day {
    min-width: 65px;
    text-align: center;
    font-size: 0.75rem;
    padding: 0.35em 0.65em;
    font-weight: 700;
    border-radius: 4px;
    line-height: 1.2 !important;
    color: #fff !important;
}
.task-link {
    color: var(--bs-body-color) !important;
    opacity: 0.8;
    text-decoration: none;
    transition: opacity 0.15s ease, color 0.15s ease, padding-left 0.15s ease;
    display: inline-block;
}
.task-link:hover {
    opacity: 1;
    color: var(--bs-link-color) !important;
    padding-left: 4px;
}
.collapse-chevron {
    transition: transform 0.2s ease;
}
.row-header[aria-expanded="true"] .collapse-chevron {
    transform: rotate(180deg);
}
.task-list-container {
    padding-left: calc(65px + 1rem) !important;
}
.row-header {
    cursor: pointer;
}
</style>

<div class="mt-4">
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
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-1/one-loop' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 2: One Loop
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-1/one-function' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 3: One Function
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-1/one-condition' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 4: One Condition
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-foundations flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-2" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-danger badge-day me-3">Day 2</span>
        <h5 class="day-title">Scratch II</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">3 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-2">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-2/odd-numbers' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 1: Odd Numbers
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-2/space-sound' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 2: Space Sound
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-2/scratch-age-in-days' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 3: Age in Days (Scratch)
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-foundations flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-3" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-danger badge-day me-3">Day 3</span>
        <h5 class="day-title">C++ Basics I</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">7 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-3">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-3/calculator' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 1: Calculator
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-3/rectangle-area' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 2: Rectangle Area
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-3/circle' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 3: Circle Properties
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-3/compare-numbers' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 4: Compare Numbers
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-3/yes-no' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 5: Yes or No
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-3/guess-number' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 6: Guess Number Type
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-3/min-max' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 7: Min Max of Three
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-foundations flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-4" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-danger badge-day me-3">Day 4</span>
        <h5 class="day-title">C++ Basics II</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">9 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-4">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/hashes' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 1: Hashes
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/numbers-1-to-n' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 2: Numbers 1 to N
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/summation' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 3: Summation
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/square-hashes' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 4: Square of Hashes
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/pyramid' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 5: Pyramid
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/min-function' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 6: Minimum Function
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/print-hello' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 7: Hello Loop Function
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/age-in-days' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 8: Age in Days
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-4/even-odd' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 9: Even or Odd Function
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-foundations flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-5" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-danger badge-day me-3">Day 5</span>
        <h5 class="day-title">Arrays</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">3 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-5">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-5/scores-greater-than-10' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 1: Scores Greater than 10
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-5/score-average' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 2: Score Average
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-5/sort-descending' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 3: Sort Descending
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-foundations flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-6" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-danger badge-day me-3">Day 6</span>
        <h5 class="day-title">Strings</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">4 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-6">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-6/substring-extractor' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 1: Substring Extractor
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-6/word-search' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 2: Word Search
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-6/censor-word' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 3: Censor Word
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-6/remove-vowels' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #e74c3c;"></i>Task 4: Remove Vowels
          </a>
        </li>
      </ul>
    </div>
  </div>

  <h3 class="track-header">Web Development</h3>
  <div class="resource-row track-web flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-12" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-primary badge-day me-3">Day 12</span>
        <h5 class="day-title">HTML</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">3 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-12">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-12/personal-profile' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 1: Personal Profile Webpage
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-12/course-registration' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 2: Online Course Registration
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-12/portfolio-website' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 3: My Portfolio Website
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-web flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-13" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-primary badge-day me-3">Day 13</span>
        <h5 class="day-title">CSS</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">3 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-13">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-13/favorite-hobby' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 1: Favorite Hobby
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-13/student-profile' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 2: Student Profile Card
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-13/portfolio-homepage' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 3: Personal Portfolio Homepage
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-web flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-14" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-primary badge-day me-3">Day 14</span>
        <h5 class="day-title">JavaScript I</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">3 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-14">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-14/personal-info' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 1: Personal Information
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-14/grade-checker' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 2: Grade Checker
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-14/favorite-day' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 3: Favorite Day
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-web flex-column align-items-start">
    <div class="d-flex align-items-center justify-content-between w-100 row-header" data-bs-toggle="collapse" data-bs-target="#collapse-day-15" aria-expanded="false">
      <div class="d-flex align-items-center">
        <span class="badge bg-primary badge-day me-3">Day 15</span>
        <h5 class="day-title">JavaScript II</h5>
      </div>
      <div class="d-flex align-items-center">
        <span class="text-secondary small me-2">3 Tasks</span>
        <i class="fas fa-chevron-down text-secondary collapse-chevron"></i>
      </div>
    </div>
    <div class="collapse w-100 task-list-container mt-3" id="collapse-day-15">
      <ul class="list-unstyled mb-0">
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-15/student-details' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 1: Student Details
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-15/favorite-movies' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 2: Favorite Movies
          </a>
        </li>
        <li class="mb-2">
          <a href="{{ '/materials/tasks/day-15/string-methods' | relative_url }}" class="task-link">
            <i class="fas fa-tasks me-2" style="color: #3498db;"></i>Task 3: String Methods
          </a>
        </li>
      </ul>
    </div>
  </div>
  <div class="resource-row track-web align-items-center justify-content-between">
    <div class="d-flex align-items-center">
      <span class="badge bg-primary badge-day me-3">Day 16</span>
      <h5 class="day-title">JavaScript III</h5>
    </div>
    <div class="text-secondary small">
      <em>To be announced...</em>
    </div>
  </div>
</div>
