# stevenbeijer.com

Website for Steven A.J. Beijer – "in the loop translations". Plain HTML, no build step. Push to `main` and GitHub Pages publishes it within a minute or two.

## Files

- `index.html` – homepage (approach, services, how it works, about, contact)
- `examples.html` – Dutch/English translation traps page
- `style.css` – all styling, shared by both pages; colours are set once at the top
- `images/steven.jpg` – portrait in the About section
- `favicon.svg` – browser-tab icon
- `CNAME` – tells GitHub Pages to serve the site on stevenbeijer.com (do not delete)

## Common edits

- Text: edit it directly in `index.html` or `examples.html`.
- New example: copy one `<article class="example">…</article>` block in `examples.html` and change the text.
- Accent colour: change `--accent` at the top of `style.css` (design alternatives: `#0F7C7A`, `#2F5BEA`, `#C8902A`), and the `#E2553A` in the inline SVGs.
- Email address: search for `stevenajbeijer@gmail.com` – it appears in several buttons on both pages.
