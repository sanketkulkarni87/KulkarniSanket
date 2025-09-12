# Copilot Instructions for Sanket HTML Programming Files

## Overview
This workspace is a collection of static HTML and CSS files for personal and portfolio web pages. There is no backend, build system, or external dependencies. All files are edited and served directly.

## Key Files & Structure
- `index.html`, `resume.html`, `applicationform.html`, `form.html`, `web.html`: Main site pages in the root directory.
- `style.css`: Shared stylesheet for root HTML files.
- `Sanketportfolio/`: Subfolder containing a separate portfolio site with its own `applicationform.html` and `style.css`.

## Patterns & Conventions
- **File Duplication:** Some files (e.g., `applicationform.html`, `style.css`) exist in both the root and `Sanketportfolio/`. Changes to one do not affect the other.
- **Styling:** Each HTML file links to its corresponding CSS file in the same directory. No CSS frameworks are used.
- **Navigation:** Inter-page navigation is handled via `<a href="...">` links. No JavaScript is present.
- **Form Handling:** Forms are present (e.g., in `applicationform.html` and `form.html`) but do not submit to a backend. If adding form logic, use only client-side validation or static handling.

## Developer Workflow
- **Edit HTML/CSS directly.** No build or test commands are required.
- **Preview changes:** Open HTML files in a browser to view updates.
- **No package management or external dependencies.**

## Examples
- To update the portfolio's application form, edit `Sanketportfolio/applicationform.html` and its styles in `Sanketportfolio/style.css`.
- To change the main site's appearance, modify `style.css` in the root directory.

## Recommendations for AI Agents
- When adding new pages, follow the naming and linking conventions used in existing files.
- Keep CSS in the same directory as the HTML it styles.
- Avoid introducing JavaScript or external libraries unless explicitly requested.
- Document any new patterns or conventions in this file for future agents.

---
For questions about unclear patterns or missing documentation, ask the user for clarification.
