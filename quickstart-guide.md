# Quickstart Guide

## Introduction

This quickstart guide will help you get started with the Plain Language Compliance Project. This project uses Docs.dev to test and improve documentation for clarity and simplicity, following the Plain Writing Act of 2010.

## Prerequisites

- GitHub account
- Basic knowledge of Git and Markdown
- Docs.dev GitHub App installed (see https://learn.docs.dev/docs)

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/vagimeli/plain-language-compliance-project.git
   ```

2. Navigate to the project directory:
   ```
   cd plain-language-compliance-project
   ```

3. Review the repository structure:
   ```
   docs-dev-test-repo/
   ├── .gitignore
   ├── README.md
   ├── Dev-Docs.JSON
   ├── datasync.py
   └── docs/
       ├── user-guide-original.md
       ├── user-guide-revised.md
       ├── plain-language-checklist.md
       └── feedback-report.md
   ```

## Using Docs.dev

1. Create documents:
   - Use Docs.dev to generate documentation for `datasync.py` using the settings in `Dev-Docs.JSON`.
   - Verify that the generated documents use simple words, active voice, and are easy to read (Grade 8 level).

2. Check documents:
   - Review `user-guide-original.md` for plain language issues such as jargon or passive voice.
   - Compare it to `user-guide-revised.md` to see the improvements.

3. Edit documents:
   - Use Docs.dev's editor to revise `user-guide-original.md`.
   - Follow the guidelines in `plain-language-checklist.md`.

4. Share feedback:
   - Document your findings in `docs/feedback-report.md`.
   - Add any issues or suggestions to the GitHub Issues tab.

## Testing Scenarios

1. Document Creation:
   - Generate documentation for `datasync.py`.
   - Check for simple language, active voice, and readability.

2. Document Review:
   - Analyze `user-guide-original.md` for plain language issues.
   - Compare it with `user-guide-revised.md`.

3. Document Editing:
   - Revise `user-guide-original.md` using Docs.dev's editor.
   - Ensure compliance with `plain-language-checklist.md`.

4. Feedback Submission:
   - Report bugs (e.g., "Missed complex word 'utilize'").
   - Suggest improvements (e.g., "Add a readability score").

## Additional Notes

- This project focuses on clear, simple writing for non-technical users.
- Ensure the Docs.dev GitHub App is properly configured for this repository.
- For questions, contact Melissa at hello@writebrainedits.com.

## Helpful Resources

- Docs.dev Quickstart: https://learn.docs.dev/docs
- Plain Writing Act: https://www.plainlanguage.gov/law/
- Plain Language Guidelines: https://www.plainlanguage.gov/guidelines/

Thank you for contributing to the improvement of Docs.dev and promoting clear communication!