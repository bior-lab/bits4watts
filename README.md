# Bits4Watts workshop website

Static HTML website hosted on GitHub Pages at https://bits4watts.org/.

## Page structure

- `index.html`: workshop directory at `/`.
- `2024/index.html`: original Osaka workshop at `/2024/`.
- `2026/index.html`: Singapore workshop at `/2026/`; content copied from 2024 pending updates.
- `assets/`: shared images and styles. `home.css` styles the directory; `main.css` and `editions.css` style the yearly pages.
- `CNAME`: existing custom domain, preserved.

Edit each year's HTML independently. Before announcing 2026, update its date, venue, program, committee, banner, and partner logos, then remove the provisional-content notice.

For another edition, copy a yearly folder and add its link to `index.html` and `sitemap.xml`. Keep asset links relative to `../assets/`.

Deploy by committing and pushing to the repository's configured GitHub Pages source. No build step is needed. Directory URLs use trailing slashes; GitHub Pages redirects `/2024` and `/2026` to their corresponding directories.

## Template credits

Based on [Mike Pierce's conference website template](https://github.com/mikepierce/conference-website-template). See `LICENSE`.
