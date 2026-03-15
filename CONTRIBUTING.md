# Contributing to the TA Recruitment System

First off, thank you for considering contributing to this project! This document outlines the standard workflow and collaboration guidelines for **Group 37** to ensure a smooth Agile development process for the EBU6304 module.

## 🌿 Branching Strategy

To maintain the integrity of our deliverables, we follow a strict **Feature Branch Workflow**. Please **do not commit directly** to the `main` branch.

* **`main`**: The stable, production-ready branch containing finalized deliverables.
* **`feature/*`**: Used for developing new documents or system features (e.g., `feature/ui-prototype`, `feature/database-design`).
* **`fix/*`**: Used for minor corrections or formatting fixes.

## 📝 Commit Message Convention

To maintain a readable and professional project history, we strictly adhere to **Conventional Commits**. Please format your commit messages as follows:

`[type]: [short description in lowercase]`

**Allowed Types:**
* `feat`: A new feature or document (e.g., adding the product backlog)
* `fix`: A bug fix or typo correction
* `docs`: Documentation only changes (e.g., updating README or CONTRIBUTING)
* `refactor`: Restructuring files or directories without changing content
* `style`: Formatting changes (e.g., CSS tweaks in the HTML prototype)

*Example:* `feat: add initial high-fidelity HTML prototype for applicant role`

## 🔄 Standard Workflow (Pull Request Process)

1.  **Sync Local Repository:** Always run `git pull origin main` before starting new work to avoid conflicts.
2.  **Create a Branch:** `git checkout -b feature/your-feature-name`
3.  **Make Changes & Commit:** Work on your assigned tasks and commit using the convention above.
4.  **Push to Remote:** `git push origin feature/your-feature-name`
5.  **Code Review & Merge:** Open a Pull Request (PR) on GitHub. Ensure at least one other team member reviews the changes before merging into the `main` branch.

## 🤝 Code of Conduct & Team Spirit

As Group 37, we are committed to fostering an open, welcoming, and collaborative Agile environment. Please ensure all discussions, document reviews, and feedback are constructive and professional. Let's build an outstanding system together!
