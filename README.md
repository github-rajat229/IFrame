# iFrame Assignment Viewer

A responsive web dashboard designed to display multiple assignment pages dynamically within a central `<iframe>` container. It features a side navigation bar with stylized buttons linking directly to individual assignments.

---

## 🚀 Features

* **Dynamic iFrame Navigation:** Uses the HTML `target` attribute to load external assignment links directly into the designated iframe without reloading the page.
* **Side Navigation Bar:** Vertical layout built with CSS Flexbox to evenly distribute navigation links (`Assignment-1` through `Assignment-10`).
* **Default Placeholder View:** Displays a full-bleed, styled cover image (`image4.jpg`) within the iframe on initial page load using the `srcdoc` attribute and CSS `object-fit: cover`.
* **Custom Button Styling:** Rounded, high-contrast dark buttons with interactive hover effects.

---

## 🛠️ Built With

* **HTML5:** `<iframe>`, `<a>`, `<button>`, and semantic content layout.
* **CSS3:** Flexbox positioning, `vh`/`vw` layout units, custom borders, border-radius styling, and iframe image-fit handling.

---

## 📦 File Structure Requirements

To ensure all assignment links load correctly in the iframe, organize your project files as follows:

```text
project-root/
│
├── index.html              # Main iframe viewer file
├── image4.jpg              # Default placeholder image
└── assests/
    ├── 1-background/
    │   └── index.html
    ├── 2-newspaper/
    │   └── index.html
    ├── 3-flex-box/
    │   └── index.html
    ├── 4-dynamic-gallery/
    │   └── index.html
    ├── 5-ui-card/
    │   └── index.html
    ├── 6-anchor/
    │   └── index.html
    ├── 8-table/
    │   └── index.html
    ├── 9-box-plot/
    │   └── index.html
    └── 10-Login/
        └── index.html
