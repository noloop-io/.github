# Contributing to noloop

Thank you for your interest in contributing to a noloop project!  
We deeply appreciate your time and effort in helping us build better, faster, and smarter software.

We maintain a clean and professional development workflow across all repositories. Please read the following guidelines carefully before submitting any contributions.

---

## 🚀 Quick Start

1. **Fork the repository** you wish to contribute to
2. **Clone your fork** and create a new branch
3. **Make your changes** with clean, tested code
4. **Submit a Pull Request (PR)** to the `develop` branch unless otherwise stated

---

## 🛠️ Requirements

Depending on the project, you may need:

- **Node.js** (latest LTS)
- **PHP 8.2+** with Composer (for Laravel projects)
- **Docker & Docker Compose**
- **Git ≥ 2.34**
- Code editor with ESLint/Prettier or PHP CS Fixer

Run the project’s `README.md` setup instructions locally before contributing.

---

## 🌿 Branching Strategy

We follow a **GitFlow-inspired** branching model:

- `main`: Stable production code
- `develop`: Active development
- `feature/*`: New features or improvements
- `fix/*`: Bug fixes
- `hotfix/*`: Urgent production fixes

Always branch from `develop` unless otherwise specified.

---

## 💬 Commit Messages

Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for clarity and automated changelogs:

```bash
feat: add new VR navigation feature
fix: resolve null exception on booking form
chore: update dependencies
