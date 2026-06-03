# Pricing cards — designer practice

A small static page with three pricing cards. No build step, no framework.
Open `index.html` in a browser to see it. Edit it in Cursor, commit, push.

## Files

- `index.html` — the content (the three cards).
- `style.css` — all styling. Colours, font and shape live in the `:root` variables at the top.

## How to run

Double-click `index.html`, or in the terminal:

```
open index.html        # macOS
start index.html       # Windows
```

`index.html` and `style.css` must sit in the same folder, or the link at the top of the HTML breaks.

## Practice tasks (easy to hard)

1. Change the page background colour. Find `--page-bg` at the top of `style.css`.
2. Change the button colour. Edit `--button-bg` and `--button-hover` in `style.css`.
3. Change a price. The prices are plain text in `index.html` (`price__amount`).
4. Edit the text on a card — title, subtitle, or an item in the `Includes` list (in `index.html`).
5. Add a fourth bullet to the "Enscape Solo" card. Copy one `<li>...</li>` line.
6. Add a fourth card. Copy a whole `<article class="card">...</article>` block and change its content.
7. Move the "Preferred choice" badge to a different card (move the `<span class="badge">` line).
8. Change the corner roundness of every card with one edit: `--card-radius` in `style.css`.

## Notes

- Content is in `index.html`, styling is in `style.css`. Start a styling task in the CSS, a text task in the HTML.
- Each card is one `<article class="card">` block with the same structure, so they are easy to copy.
