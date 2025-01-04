# Organization

Welcome to the central hub for the Danish Data Science Community's organizational documentation. This repository houses the governing documents, policies, and guidelines that define the structure and operations of our various initiatives, committees, and projects.

The complete documentation is available at: https://dansk-data-science-community.github.io/organization/

## Contributing to the Documentation
1. Make your changes:
   - Documentation files are located in `docs/`
   - Files use reStructuredText format (.rst)
   - Edit existing files or create new ones as needed

2. Build the documentation locally:
   ```bash
   cd docs
   make html
   ```
   The built documentation will be available in `docs/_build/html/`

3. Preview changes:
   - Open `docs/_build/html/index.html` in your web browser
   - Or serve it locally using Python:
     ```bash
     python -m http.server --directory _build/html
     ```
4. Publish changes
   Commit your changes and push to the main branch
-  The documentation will automatically build and deploy via GitHub Actions
- Changes will be live in a few minutes at the documentation URL