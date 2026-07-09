# BNETCORE Solutions — Website

Static, zero-build marketing site for BNETCORE Solutions. No Node/build step required — open `index.html` directly or serve the folder with any static file server.

## Structure

- `index.html` — the main site (Hero, Services, About Us, Blog, Contact). Nav/theme/language behavior lives in `assets/js/main.js`.
- `post.html` — sample blog article detail page.
- `assets/styles/theme.css` — CSS variables for the dark/light themes, background grid, and the hero atom animation.
- `assets/js/main.js` — i18n (EN/RO) dictionary, dark/light/system theme controller, mobile menu, smooth scroll, and the contact form submit handler (Web3Forms).
- `assets/img/` — images referenced by the pages above.

Tailwind CSS and Font Awesome are loaded via CDN (`<script src="https://cdn.tailwindcss.com">` and the Font Awesome CSS `<link>`) — there is nothing to install or compile.

## Notes

- The Portfolio section is commented out in `index.html` (search for "Portfolio section intentionally hidden") until there are real client projects to show — the markup and styling are kept in place.
- See `TODO.md` for the outstanding roadmap.
