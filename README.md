Elegance Furnishings — Project Structure

Structure
- index.html           Root landing page
- pages/               All sub-pages (aboutUs, gallary, form, concat, otp*)
- assets/css/          All stylesheets (global + page-specific)
- assets/img/          All images (moved from img/)
- assets/js/           Placeholder for scripts

Conventions
- Global styles in assets/css/style.css
- Each page loads its own stylesheet from assets/css/<page>.css
- Images referenced via ./assets/img/... (from root) or ../assets/img/... (from pages)

Updating Links
- From root: href="./assets/css/style.css", src="./assets/img/<file>"
- From pages: href="../assets/css/<file>", src="../assets/img/<file>"

Notes
- Keep file names as-is for now (e.g., gallary.html) to avoid broken links.
- Consider renaming "gallary" to "gallery" later with redirects or link updates.