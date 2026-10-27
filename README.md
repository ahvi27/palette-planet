# 🎨 Palette Planet

### A little universe of color for your next big idea.

Palette Planet is a responsive color palette generator built with
HTML, CSS, and JavaScript. Explore different moods, lock the colors
you love, and copy your palette into your next design project.

## ✨ Features

- **Five-color palettes** generated with one click
- **Five moods:** Dreamy Pastels, Earthy Escape, Bright Energy,
  Ocean Breeze, and Anything Goes
- **Color locking** to keep favorites while generating new combinations
- **Hex code copying** for individual colors
- **CSS export** to copy the palette as custom properties
- **Keyboard shortcut:** press Space to generate
- **Responsive design** for desktop and mobile
- **Accessible controls** with labels, focus indicators, and status messages
- **Reduced-motion support** based on browser preferences

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Browser Clipboard API

No framework, package installation, account, or API key is required.

## 🚀 Getting Started

### 1. Clone the repository

Replace `YOUR-USERNAME` with your GitHub username:

```bash
git clone https://github.com/YOUR-USERNAME/palette-planet.git
cd palette-planet
```

### 2. Start a local server

```bash
python3 -m http.server 8000
```

On Windows, you can use:

```bash
py -m http.server 8000
```

### 3. Open the website

Visit:

```text
http://localhost:8000
```

Press **Ctrl+C** in the terminal to stop the server.

You can also open `index.html` directly to generate palettes.
Clipboard buttons work best on **localhost or HTTPS**.

## 🪄 How to Use

1. Select a palette mood.
2. Click **Generate** or press **Space**.
3. Lock any color you want to keep.
4. Generate again to discover new colors around your favorites.
5. Click **Copy** beside a color to copy its hex code.
6. Click **Copy CSS** to copy all five colors as CSS variables.

The Space shortcut is inactive while using a button, link, or form field.

## 🎨 Example CSS Output

```css
:root {
  --color-1: #E6C9E8;
  --color-2: #C7B4EA;
  --color-3: #A8BDE0;
  --color-4: #B9D8D0;
  --color-5: #F1D3C5;
}
```

Use these variables in your own project:

```css
body {
  background: var(--color-1);
}

button {
  background: var(--color-3);
}
```

## 📁 Project Structure

```text
palette-planet/
├── index.html
└── README.md
```

The HTML file contains the page structure, styles, and JavaScript.

## 📝 Notes

- Generated palettes and locked colors reset when the page reloads.
- Clipboard access requires a secure context, such as localhost or HTTPS,
  and may depend on browser permissions.
- If copying is unavailable, you can select the visible hex codes manually.
- The website chooses black or white text for its color cards. Check
  contrast separately when combining palette colors in your own designs.

## 🎯 Project Goal

Palette Planet helps creators quickly explore colors and find a
starting point for websites, brands, and other visual projects.

---

**Made for curious creators. ✦**
