# Master Resume — Manual Test Suite

**Feature Under Test:** Master Resume System  
**Submission Type:** Manual Test Suite (Markdown)  

---

## Overview
This repository contains a manual test suite for the Master Resume system. It validates core features including form inputs, validation rules, file uploads, and optimization behavior. 

The objective is to ensure functional correctness and consistent system behavior across all resume modules.

## Objectives
* Validate form input correctness.
* Ensure proper data validation rules.
* Verify file upload behavior.
* Validate optimization output consistency.
* Provide structured and repeatable QA coverage.

---

## Test Coverage

| File | Feature | Test IDs |
| :--- | :--- | :--- |
| `TC-01–TC-03-contact-info.md` | Contact Information | TC-01–TC-03 |
| `TC-04-summary.md` | Professional Summary | TC-04 |
| `TC-05-skills.md` | Skills Input | TC-05 |
| `TC-06-portfolio-projects.md` | Portfolio Projects | TC-06 |
| `TC-07–TC-08-employment-history.md` | Employment History | TC-07–TC-08 |
| `TC-09-education.md` | Education | TC-09 |
| `TC-10-references.md` | References | TC-10 |
| `TC-11-save-behavior.md` | Save Functionality | TC-11 |
| `TC-12-optimization-observation.md` | Optimization Output | TC-12 |
| `TC-13–TC-17-upload-flow.md` | CV Upload Flow | TC-13–TC-17 |

---

## Repository Structure

```text
master-resume/
│
├── README.md
│
├── master-resume/
│   ├── TC-01-TC-03-contact-info.md
│   ├── TC-04-summary.md
│   ├── TC-05-skills.md
│   ├── TC-06-portfolio-projects.md
│   ├── TC-07-TC-08-employment-history.md
│   ├── TC-09-education.md
│   ├── TC-10-references.md
│   ├── TC-11-save-behavior.md
│   └── TC-12-optimization-observation.md
│
└── upload-cv/
    └── TC-13-TC-17-upload-flow.md
```
## How to Run Tests

* Clone the repository: git clone https://github.com/AKMC-mapua-makati/ceevee-qa-report.git
* Open the specific test case files you wish to execute.
* Execute each test step in the order provided.
* Compare the actual results in the system against the expected output in the documentation.

## Status

All test cases are designed for manual execution. Status values are maintained within the individual test case files using the following definitions:

* **Pass:** Meets expected results.
* **Fail:** Deviates from expected results.
* **Blocked:** Cannot be tested due to dependencies.
* **Untested / WIP:** Not yet executed.
