# baili-quotation-tool

Quotation tool for Baili Electrical Appliance.

This project is a simple static website built with HTML, CSS, and JavaScript. It is designed for beginners and does not require any install steps or build tools.

## Project structure

- `index.html` — page layout
- `styles.css` — page styling
- `script.js` — quotation calculation logic

## How to use

1. Open `index.html` directly in a browser, or
2. Run a simple local web server:

```bash
cd /path/to/baili-quotation-tool
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Common beginner problems and solutions

### 1. 页面是空白的
- Check whether the three files exist in the same folder: `index.html`, `styles.css`, `script.js`.
- Make sure the file name matches exactly in the HTML code.
- Example: `<link rel="stylesheet" href="styles.css">` and `<script src="script.js"></script>`

### 2. 点击按钮没有反应
- Open the browser developer tools and check the Console tab.
- Usually this means there is a JavaScript syntax error.
- Common reasons:
  - missing comma or semicolon
  - wrong element ID name
  - using wrong variable names

### 3. 样式没有显示出来
- Check whether `styles.css` is in the same directory as `index.html`.
- In `index.html`, the path must be correct.
- Example: `href="styles.css"` is correct; `href="./css/styles.css"` will only work if the folder exists.

### 4. 代码不想写时，先从最简单开始
- Start with static text and make sure the page loads.
- Then add the form and calculation logic gradually.
- For beginners, do not rush into frameworks or package installation.

This project is intentionally simple so it is easy to understand and learn from.
