# forma® – Product Showcase Page

🔗 **Live demo:** https://thang2712.github.io/forma/

A clean, minimalist product listing page for **forma®**, a fictional store
selling desk and workspace accessories. Built with HTML, CSS and a small
amount of vanilla JavaScript as a front-end practice exercise.

## Features

- **Flexbox-only layout.** The header, hero, product grid and footer all use Flexbox.
  The product grid uses `flex-wrap` with a `calc()`-based `flex-basis` to make an
  even 3-column layout.
- **Responsive design.** The grid goes from 3 columns to 2 columns (≤ 900px) to
  1 column (≤ 600px). The navigation hides on smaller screens and the hero stacks vertically.
- **CSS custom properties.** Colors and spacing are defined once in `:root`,
  so the whole theme is easy to adjust.
- **Product cards.** Each card has an image, a pastel background,
  a numbered label, an optional "favorite" tag, a description and a price.
- **Interactive cart counter.** Clicking "Mua ngay" (Buy now) increases the cart
  count in the header, using a few lines of vanilla JavaScript.
- **Accessible details.** Images have `alt` text and buttons use `:focus-visible` outlines.

## Project Structure

```
├── index.html     # Page markup
├── style.css      # All styles
└── img/           # Product images
```

## Tech Stack

- HTML5
- CSS3 (Flexbox, custom properties, media queries)
- Vanilla JavaScript

## Getting Started

Clone the repo and open `index.html` in your browser.
No build step required.

## Author

**Teejaze** – [GitHub](https://github.com/Thang2712)
