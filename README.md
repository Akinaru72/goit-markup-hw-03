# goit-markup-hw-03

- Create a repository **goit-markup-hw-03**.
- Clone the created repository and copy the files from the previous assignment into it.
- Add styles for geometry (widths, spacing, margins, and borders) and content positioning using **Flexbox** for the layout pages of **[homework #3](<https://www.figma.com/file/wuEpGhwCepGCOUw7mZFRac/Web-Studio-(Version-5.0)?type=design&node-id=302815-2553&mode=design&t=HqslgV0OjDOknzIj-0>)**.
- Set up **GitHub Pages** and add a link to the live page in the **About** section of the GitHub repository.

---

## A — Project

- **A1** — There is an `images/` folder with images in the project root.
- **A2** — There is a `css/` folder with a styles file in the project root.
- **A3** — All styles are written in a single `styles.css` file located in the `css/` folder.
- **A4** — File names do not contain uppercase letters, spaces, or transliteration — only lowercase English letters.
- **A5** — The source code is formatted using **Prettier**.
- **A6** — All images and text content are taken from the layout.
- **A7** — The **[modern-normalize](https://github.com/sindresorhus/modern-normalize)** style normalizer is connected.
- **A8** — The code is written following the recommendations of **[Code Guide](https://codeguide.co/)**.

---

## B — Styling

- **B1** — Global reset of styles for `h1–h6`, `p`, `ul` is allowed.
- **B2** — Elements do not have external margins (`margin`) that collapse outside the parent element.
- **B3** — Vertical spacing between adjacent elements is set using `margin`.
- **B4** — The space between the parent element’s border and the content is set using `padding`.
- **B5** — The values of `margin` and `padding` exactly match the layout.
- **B6** — A common helper class `.container` is created to center the content.
- **B8** — The container width matches the layout and is **1158px**.
- **B9** — The container is placed inside the `header`, `footer`, and all sections.
- **B10** — **Flexbox** is used for element positioning only where necessary.
- **B11** — The final block sizes in the browser match the layout.
- **B12** — Elements do not have a fixed height — it is determined by the content.
- **B13** — The header has a bottom border (`border-bottom`) visible when the layout is strongly zoomed in.
- **B14** — Sections are placed one below another without external margins.
- **B15** — All sections have the `.section` class with top and bottom `padding` of **120px**.
- **B16** — The **visually-hidden** pattern is used to hide a heading:

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

- **B17** — Cards in the **Our Portfolio** section have a border (`border`) only at the bottom of the card.

---

## Resources

- **[Figma layout](<https://www.figma.com/file/wuEpGhwCepGCOUw7mZFRac/Web-Studio-(Version-5.0)?type=design&node-id=296641-536&mode=design>)**
- **[modern-normalize](https://github.com/sindresorhus/modern-normalize)**
- **[Code Guide](https://codeguide.co/)**

---

**Live page: [GitHub Pages](https://akinaru72.github.io/goit-markup-hw-03/)**
