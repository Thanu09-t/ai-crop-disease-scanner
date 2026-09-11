# Contributing to AgriScan Pro

First off, thank you for considering contributing to **AgriScan Pro**! It's people like you that make agriculture technology accessible and impactful for growers worldwide.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

---

## Code of Conduct

This project and everyone participating in it is governed by the [AgriScan Pro Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

---

## How Can I Contribute?

### 1. Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When filing a bug report using our [Bug Report Template](.github/ISSUE_TEMPLATE/bug_report.md), include:
- A clear, descriptive title.
- Steps to reproduce the issue.
- Expected behavior vs. actual behavior.
- Operating system, browser version, and screen resolution.
- Screenshots or screen recordings if applicable.

### 2. Suggesting Enhancements

Feature requests are tracked as GitHub issues. When creating a feature suggestion via our [Feature Request Template](.github/ISSUE_TEMPLATE/feature_request.md):
- Explain why this enhancement would be useful to AgriScan Pro users.
- Describe the proposed interface, workflow, or architectural change.
- Provide mockups or design references if available.

### 3. Submitting Pull Requests

1. **Fork the repository** and create your branch from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. **Make your changes**:
   - Ensure clean HTML structure and semantic markup.
   - Maintain the design language: Tailwind CSS utility classes, cohesive color palettes, and Material Symbols.
   - Verify that your layout is fully responsive across mobile, tablet, and desktop viewports.
3. **Test locally**:
   - Serve the files via `python -m http.server 8000` or `npx serve`.
   - Verify that navigation links between screens function accurately.
4. **Commit your changes**:
   - Write clear, concise commit messages following standard conventions:
     ```text
     feat: add export pdf button in treatment guides
     fix: correct aspect ratio of camera preview on mobile
     docs: update local development commands in README
     ```
5. **Push to your fork and submit a PR**:
   - Open a pull request against the `main` branch.
   - Fill out the [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md).

---

## Code Style & Conventions

- **Semantic HTML**: Always use appropriate tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<button>`, `<a>`).
- **Icons**: Utilize Google Material Symbols Outlined icons (`<span class="material-symbols-outlined">icon_name</span>`).
- **Typography**: Inter font family is the standard font.
- **Palette**: Use the defined brand tones:
  - Dark Spruce: `#012d1d`
  - Emerald Green: `#116c4a`
  - Light Mint: `#a1f4c8`
  - Canvas Neutral: `#f8f9fa` / `#191c1d`

---

## Questions or Support?

Feel free to open a Discussion or issue on GitHub. Thank you for contributing!
