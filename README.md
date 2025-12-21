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

- **B17** — Cards in the "Our Portfolio" section have a border only at the bottom

---

## Resources

- [Code Guide](https://codeguide.co/) — coding style guide

---

**Live page:** [GitHub Pages](https://akinaru72.github.io/goit-markup-hw-03/)
