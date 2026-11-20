# Agent instructions

## Project shape

- This is a static Vietnamese education portal. The application is implemented in `index.html`, with its CSS and JavaScript embedded in that file.
- There is no package manifest or automated test suite in this folder. Avoid adding build tooling for small changes.
- Keep user-facing text in Vietnamese and preserve the existing single-page structure unless a requested change requires otherwise.

## Change guidelines

- Keep markup IDs and the JavaScript that uses them in sync.
- Preserve role checks for students, teachers, and administrators when changing navigation or data actions.
- Update `USER_MANUAL.md` when user-visible workflows or limitations change.
- Treat the `vnsedu_*` browser-storage keys as persisted data. Renaming a key requires an explicit migration.
- Do not add account passwords, tokens, or real student information to source code or documentation.
- Authentication and application data are demo-only and stored in the browser. Do not describe client-side role checks or password hashing as production security; real deployments require a trusted backend.

## Validation

- For JavaScript changes, check the inline script for syntax errors when Node.js is available.
- Smoke-test the affected workflow in a browser, including the relevant role where possible.
- There is no automated test command configured in this project.
