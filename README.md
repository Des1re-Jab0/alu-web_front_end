# Responsive design

Makes the Techium homepage and article page responsive, step by step, using
flexible containers, media queries, responsive images and a pure HTML/CSS
mobile menu (no JavaScript).

## Breakpoints

| Device          | Media query        |
| ---             | ---                |
| Extra large     | none               |
| Desktop / large | `max-width: 992px` |
| Tablet / medium | `max-width: 767px` |
| Mobile          | `max-width: 480px` |

## Files

| Task | Files                                | What changes                                             |
| --   | ---                                  | ---                                                      |
| 0    | `01-index.html`, `01-styles.css`     | Fixes the hero banner background                         |
| 1    | `02-index.html`, `02-styles.css`     | Container uses `max-width`                               |
| 2    | `02-1-index.html`, `02-1-styles.css` | Fluid images, stacked grid, navbar hidden under 767px    |
| 3    | `03-index.html`, `03-styles.css`     | `srcset` and `sizes` on the About and Latest News images |
| 4    | `04-index.html`, `04-styles.css`     | Checkbox and label that will drive the mobile menu       |
| 5    | `05-index.html`, `05-styles.css`     | Hamburger icon drawn with CSS                            |
| 6    | `06-index.html`, `06-styles.css`     | Menu opens and closes from the checkbox state            |
| 7    | `07-index.html`, `07-styles.css`     | Responsive font size                                     |
| 8    | `08-index.html`, `08-styles.css`     | Works cards show their titles on small screens           |
| 9    | `09-index.html`, `09-styles.css`     | Footer layout on small screens                           |
| 10   | `10-index.html`, `10-styles.css`     | Header background fix with the `article-page` class      |
| 11   | `100-article.html`, `100-styles.css` | Responsive article page                                  |

## Images

All pictures live in the `images` directory at the root of the project.
