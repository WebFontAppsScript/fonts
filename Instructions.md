# 🛠️ Instructions.md

This project is called **WebFont**, a simple yet powerful web font library platform built using HTML, CSS, and JavaScript.

## 📁 Hosting Setup

- The **main HTML file** is hosted using **Google Apps Script Web App**.
- All **supporting files** (JavaScript, CSS, README, JSON/font data, etc.) are stored and managed through **GitHub**.
- This separation allows for fast loading via Apps Script and flexible updates through GitHub.

## 🚀 How It Works

1. The HTML file (`index.html`) is deployed as a **Google Apps Script Web App**.
2. Font definitions and JS logic are served or linked from GitHub.
3. Users can preview fonts, copy CSS embed codes, and download them directly.

## 💾 How to Add Fonts

1. Go to the `index.html` file in Apps Script.
2. Inside the `<script>` tag, use this function format:

```javascript
addFont({
  name: "Open Sans",
  fontUrl: "https://fonts.googleapis.com/css2?family=Open+Sans&display=swap",
  previewFontFamily: "'Open Sans', sans-serif",
  downloadUrl: "https://fonts.google.com/download?family=Open+Sans"
});
