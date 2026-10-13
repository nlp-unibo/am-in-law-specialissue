# Codebase schema

## `index.html`

Static entry point containing page metadata, navigation, call details, editorial policies, guest-editor profiles, and contact information.

Dependencies:

- Loads `style.css` for presentation and responsive layout.
- Loads guest-editor images from `img/people/`.
- Links to AI & Law and Springer Nature policy pages.

## `style.css`

Defines global typography, colors, page sections, notices, editor profiles, and responsive behavior. It is loaded directly by `index.html`.

## `.github/workflows/docs.yml`

Deploys repository root to GitHub Pages after each push to `main` or a manual workflow run.
