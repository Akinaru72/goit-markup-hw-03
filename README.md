# goit-markup-hw-03

**Homework #3:** Layout page with geometry, spacing, and Flexbox positioning.

Set up GitHub Pages and add a link to the live page in the **About** section of the repository.

---

## A — Project

- **A1** — The project root contains an `images/` folder with images.
- **A2** — The project root contains a `css/` folder with the stylesheet.
- **A3** — All styles are written in a single `styles.css` file inside the `css/` folder.
- **A4** — File names contain **no uppercase letters, spaces, or transliteration**; only lowercase English letters and words.
- **A5** — Code formatted using **Prettier**.
- **A6** — All images and text content are taken from the design layout.
- **A7** — [modern-normalize](https://cdnjs.com/libraries/modern-normalize) is included.
- **A8** — Code follows the [Code Guide](https://codeguide.co/) recommendations.

---

## B — Layout & Styling

- **B1** — Global reset is allowed for heading tags `<h1>...<h6>`, `<p>` and `<ul>`.
- **B2** — Elements have no external margins that break the parent element.
- **B3** — Vertical spacing between two neighboring elements is set using `margin`.
- **B4** — Padding is used for spacing between parent border and child content.
- **B5** — Margin and padding values match the layout exactly.
- **B6** — A general helper class `.container` is created for centering and limiting content width.
- **B8** — Container width matches the design (1158px).
- **B9** — The container wraps the content of the header, footer, and sections (inside them).
- **B10** — Flexbox is used only where necessary (header, navigation, section lists, etc.).
- **B11** — Final block sizes in the browser match the layout.
- **B12** — Elements do not have fixed height; height is determined by their content.
- **B13** — The header has a bottom border for precise design alignment.
- **B14** — Sections are stacked one under another like books, without external spacing.
- **B15** — All sections use a `.section` class with `padding-top` and `padding-bottom` set to 120px.
- **B16** — Hidden headings use the `visually-hidden` pattern:

```css
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  border: 0;
  padding: 0;
  white-space: nowrap;
  clip-path: inset(100%);
  clip: rect(0 0 0 0);
  overflow: hidden;
}
```

---

## C — Visual Design & Flexbox

- **C1** — Styling uses class selectors only.
- **C2** — No `!important` in styles.
- **C3** — Interactive elements (buttons and links) have active states on hover and focus, as per style guide.
- **C4** — Header contact text changes color on hover and focus.
- **C5** — `font-family` on `<body>` uses dominant font from layout (Roboto).
- **C6** — Alternative fonts and fallback sans-serif declared at the end of `font-family`.
- **C7** — Roboto font-family explicitly declared only on `<body>`, other elements inherit.
- **C8** — `<body>` text color set to dominant color from layout; other text inherits or overrides this.
- **C9** — Font-size of all text elements matches layout exactly.
- **C10** — Line-height of all text elements matches layout and set as a multiplier, not in px.
- **C11** — Colors (`color` and `background-color`) match layout exactly.
- **C12** — Font-weight matches layout; explicitly set only if different from browser default.
- **C13** — Buttons have `cursor: pointer`.
- **C14** — Styles do not repeat browser default values (e.g., no need for `cursor: pointer` on links or `font-weight: 400` on paragraphs).

---

## Resources

- [Squoosh](https://squoosh.app/) — image optimization
- [Code Guide](https://codeguide.co/) — coding style guide
- [W3C Validator](https://validator.w3.org/nu/#textarea) — HTML validation
- [modern-normalize](https://github.com/sindresorhus/modern-normalize) — CSS normalization

---

**Live page:** [GitHub Pages](https://akinaru72.github.io/goit-markup-hw-03/)
