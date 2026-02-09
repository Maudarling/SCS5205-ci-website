[![Deploy static content to Pages](https://github.com/Maudarling/SCS5205-ci-website/actions/workflows/static.yml/badge.svg)](https://github.com/Maudarling/SCS5205-ci-website/actions/workflows/static.yml)
# Maudy Musundire | Personal Portfolio

This is a clean, professional, and responsive personal website designed to showcase my academic journey as a Master's student at **NUST University**.

## 👤 About Me
* **Name:** Maudy Musundire
* **Age:** 26
* **Occupation:** Master's Student at NUST
* **Focus:** Academic research, professional development, and technical innovation.

## 🚀 Features
- **Modern UI:** A minimalist design using a professional color palette.
- **Mobile Responsive:** Optimized for viewing on desktops, tablets, and mobile devices.
- **Academic Highlights:** Dedicated sections for education and research focus.
- **Linted CSS:** Follows industry standards for clean code using Stylelint.
- **CI/CD Workflow Documentation
For this project, I implemented a Continuous Integration (CI) pipeline using GitHub Actions. This ensures that every time I contribute to the codebase, the changes are automatically validated to maintain high standards.

How the Pipeline Works:
Trigger: The workflow is triggered on every push or pull_request to the main branch.

Environment: The jobs run on a virtual ubuntu-latest server.

Validation Steps:

Linting: Uses Stylelint to analyze style.css for syntax errors and inconsistent formatting.

HTML Validation: Uses html-validate to check index.html for broken tags, accessibility issues (like missing alt text), and structural integrity.

Reporting: If any step fails, a Red X appears, and the deployment is halted. If all steps pass, a Green Checkmark confirms the code is production-ready.

## 📂 Project Structure
```text
├── index.html          # Main structure of the website
├── style.css           # Custom styles and layout
└── .stylelintrc.json   # Configuration for CSS linting
