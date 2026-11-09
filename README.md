# octoCat-dateFormatter

A small browser-based date formatter built as a JavaScript practice project alongside a freeCodeCamp assignment. It displays today's date and lets you choose between three formats.

![Date formatter preview](https://github.com/matwal42083/octoCat-dateFormatter/assets/115494989/5ad38237-a07d-4c88-8562-1f05e32409d9)

## Date formats

Choose a format from the dropdown:

| Option | Example format |
| --- | --- |
| Day, Month, Year | `9-11-2026` |
| Year, Month, Day | `2026-11-9` |
| Month, Day, Year, Hours, Minutes | `11-9-2026 22 Hours 49 Minutes` |

The date and time are read from the browser's local clock when the page loads. The displayed values use JavaScript's `Date` object.

## Run locally

Open [`date formatter/index.html`](date%20formatter/index.html) in a browser. The page loads its CSS and JavaScript from the same directory; no installation or build step is needed.

## Project files

- `date formatter/index.html` — page structure and format selector.
- `date formatter/styles.css` — page styling, including a small-screen adjustment at widths up to 375px.
- `date formatter/script.js` — reads the current date and updates the display when the selected format changes.

## Technologies

- HTML
- CSS
- JavaScript

This is a practice project from a code collection, not a deployed application.