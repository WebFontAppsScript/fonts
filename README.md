# WebFont

**WebFont** is a sleek, all-in-one web application for previewing, downloading, and embedding web fonts. Whether you're building a website, designing a logo, or just browsing cool typography, WebFont makes it easy to find the perfect typeface.

## 🌟 Features

- Live previews of each font with customizable sample text
- Direct font download links
- CSS embed codes for fast implementation
- Easy-to-edit JavaScript for adding new fonts
- No frameworks — just clean HTML, CSS, and JavaScript

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Add new fonts easily using the `addFont()` function in the script section.

## 🧩 Adding Fonts

To add a new font, use the `addFont()` function in `index.html` like this:

```js
addFont({
  name: "Roboto",
  fontUrl: "https://fonts.googleapis.com/css2?family=Roboto&display=swap",
  previewFontFamily: "'Roboto', sans-serif",
  downloadUrl: "https://fonts.google.com/download?family=Roboto"
});
