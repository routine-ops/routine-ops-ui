# Contributing to Routine-Ops UI

Thank you for considering contributing to **routine-ops-ui**! We welcome improvements, bug fixes, and enhancements. To keep the project organized and maintain high quality, please follow these guidelines:

---

## 1. Code of Conduct

All contributors must abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please treat everyone with respect and kindness.

## 2. Getting Started

1. **Fork the repository** on GitHub.
2. **Clone** your fork locally:

   ```bash
   git clone git@github.com:<your-username>/routine-ops-ui.git
   cd routine-ops-ui
   ```
3. **Install dependencies**:

   ```bash
   npm install
   ```
4. **Set up environment variables**:

   ```bash
   cp .env.local.example .env.local
   # Fill in required values
   ```
5. **Start the development server**:

   ```bash
   npm run dev
   ```

## 3. Branching Strategy

- Use **feature branches** off `main`, each named after your JIRA or Kanban ticket ID and a short description.
- Branch naming conventions:
  - **Feature:** `feature/<JIRA-ID>-short-description`  
    _e.g._ `feature/ROUT-123-add-dark-mode`
  - **Bugfix:** `bugfix/<JIRA-ID>-short-description`  
    _e.g._ `bugfix/ROUT-124-fix-button-alignment`
  - **Chore:** `chore/<JIRA-ID>-description`  
    _e.g._ `chore/ROUT-125-update-dependencies`

## 4. Coding Standards

* **Language & Formatting**: TypeScript + React.
* **Linting**: We use ESLint and Prettier.

  ```bash
  npm run lint
  npm run lint:fix
  ```
* **Style**: Follow existing code patterns and Tailwind utility classes.

## 5. Writing Code

* **Small, focused commits**: each commit should encapsulate a single logical change.
* **Atomic PRs**: limit each pull request to one feature or bug fix.
* **Tests**: include unit tests for new functionality or bug fixes using Jest.

  ```bash
  npm run test
  ```
* **Types**: ensure all new code is fully typed; avoid `any` where possible.

## 6. Pull Request Process

1. **Open an issue** using our [Issue Template](.github/ISSUE_TEMPLATE/development.yml) to discuss your proposed change (unless it’s a typo/docs fix).
2. **Create a branch** for your change.
3. **Make your changes**, **write tests**, and **ensure all checks pass** (lint, tests, build).
4. **Push** your branch and **open a PR** against the `main` branch.
5. **Fill out the PR template**, referencing the related issue (e.g., `Closes #123`).
6. **Wait for review**. Address feedback by updating your branch.

## 7. Releases & Changelog

* We maintain a `CHANGELOG.md` following [Keep a Changelog](https://keepachangelog.com/).
* For major changes, label PRs with `major`, `minor`, or `patch` via labels to automate release notes.

## 8. Reporting Security Issues

Do not create a public issue. Instead, email **[security@routine-ops.com](mailto:security@routine-ops.com)** with details, and we will respond promptly.

---

Thank you for helping make **routine-ops-ui** better! 🎉
