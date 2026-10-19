# MangaShelf

Student frontend project for Assignments 1–4: a multi-page manga catalog built with **HTML5**, **CSS3 (Flexbox & CSS Grid)**, and **Bootstrap 5.3**. There is **no JavaScript** — the next assignments cover that.

Open `index.html` in a browser (double-click or Live Server). All pages share one dark theme, navbar, and footer.

## Pages

| File | Role | Techniques shown |
| --- | --- | --- |
| `index.html` | Home | Semantic tags (`header`, `nav`, `main`, `section`, `aside`, `footer`), hero block, Flexbox equal-height cards |
| `catalog.html` | Catalog | CSS Grid two-column layout, 6+ cards, styled HTML table |
| `details.html` | Title page | `grid-template-areas`, lists, `relative` / `absolute` badges |
| `reading.html` | Reader gallery | CSS Grid + `gap`, `:hover` scale/shadow, `@media` queries |
| `contact.html` | Register & contact | Full registration form, feedback `textarea`, HTML5 validation, Bootstrap `is-valid` / `is-invalid` |
| `styles.css` | Theme | Dark palette, layout, hover, responsive rules |

## Design tokens

- Background `#121212`
- Cards `#1e1e24`
- Accent `#6C5CE7`
- Text `#E0E0E0`

Bootstrap 5.3 CSS is loaded from the official CDN. Custom rules live in `styles.css`. The mobile menu uses a CSS checkbox so the navbar works **without** Bootstrap JS.

## Assignment map

1. **Structure & semantics** — landmarks on every page, consistent nav/footer.
2. **Flexbox & Grid** — home cards, catalog sidebar/grid, details areas, reading gallery.
3. **Tables, positioning, hover, media queries** — ranking table, cover badges, gallery hover, tablet/phone breakpoints.
4. **Forms** — required fields, `type="email"`, `minlength` / `maxlength`, radios, checkboxes, select, submit/reset, Bootstrap validation samples, `col-md-6` / `col-12`.

## How to present it

1. Start on Home and show the hero + equal-height cards.
2. Open Catalog: point at the two-column Grid and the striped ranking table.
3. Open Details: name the grid areas and the TOP / 18+ badges.
4. Open Reading: hover a page (scale + shadow), then shrink the window for media queries.
5. Open Contact: walk through registration fields, then the valid/invalid example states.

Cover photos are placeholder images from Unsplash (atmosphere only, not licensed manga pages).
