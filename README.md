[![Deploy static content to Pages](https://github.com/Maudarling/SCS5205-ci-website/actions/workflows/static.yml/badge.svg)](https://github.com/Maudarling/SCS5205-ci-website/actions/workflows/static.yml)
# Maudy Musundire | Personal Portfolio

This website serves as a professional digital portfolio for Maudy Musundire, a 26-year-old Master's student at the National University of Science and Technology (NUST). The goal of the project is to showcase academic achievements, research interests, and technical proficiency in a clean, accessible format.

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
- 
**CI Workflow Setup**
This project implements a Continuous Integration (CI) pipeline using GitHub Actions to automate code validation and quality control.

1. Workflow Configuration
The workflow is defined in .github/workflows/ci.yml and is triggered on every push or pull request to the main branch.

2. Validation Steps
The pipeline executes a series of automated jobs to ensure the site's integrity:

Environment Setup: Initializes a virtual Ubuntu environment and installs Node.js.

CSS Linting: Uses Stylelint with the stylelint-config-standard to catch syntax errors and enforce consistent formatting in style.css.

HTML Validation: Employs html-validate to check index.html for structural errors, missing attributes, and non-encoded characters.

3. Monitoring
The success or failure of the build is visually represented by a status badge at the top of this document. A Green Checkmark indicates the code is valid and production-ready, while a Red X alerts the developer to errors that must be fixed.
## 📂 Project Structure
```text
├── index.html          # Main structure of the website
├── style.css           # Custom styles and layout
└── .stylelintrc.json   # Configuration for CSS linting

Conclusion & Reflection
The implementation of this Continuous Integration (CI) pipeline successfully automated the validation process for the Maudy Musundire Portfolio project. Through the use of GitHub Actions, I bridged the gap between manual coding and automated quality assurance.

Key Takeaways:
Automated Quality Control: By integrating Stylelint and html-validate, I ensured that the project adheres to modern W3C standards. The pipeline caught several critical issues—including legacy CSS color notations and unencoded HTML characters—that might have been overlooked during manual testing.

Version Control & History: The transition from failed builds (Red X) to successful builds (Green Check) provided a transparent audit trail of the debugging process. This iterative approach is essential in professional software development to maintain a "clean" and deployable main branch.

Scalability: While this project is currently a static website, the CI framework established here is scalable. It provides a foundation for adding more complex tests, such as accessibility audits or automated deployments to hosting services like GitHub Pages.

By completing this task, I have gained practical experience in configuring YAML-based workflows and managing linter configurations, reinforcing the importance of Continuous Integration in delivering robust, error-free web applications.
