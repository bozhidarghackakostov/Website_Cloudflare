# Bozhidar Kostov - Personal Landing Page

A clean, lightweight, single-page personal website and links hub for **Bozhidar "G" Kostov**, configured for deployment on static hosting platforms such as **Cloudflare Pages**.

---

## 📌 Overview

This repository contains the source code for a centralized personal landing page designed to direct visitors to various personal projects, social media channels, and professional portfolios across the web.

### Features
- **Semantic HTML5**: Clean structure using standard `<header>`, `<main>`, `<section>`, and `<footer>` elements.
- **Embedded SVG Icons**: Crisp vector brand icons for all linked platforms (WordPress, YouTube, GitHub, Behance).
- **Security & Accessibility**: External links configured with `target="_blank"`, `rel="noopener noreferrer"`, and descriptive `aria-label` tags.
- **Extensible**: Includes modular link references to external styling (`style.css`) and script logic (`script.js`).
- **Zero-Dependency**: Fast-loading static page with no external build tools or frameworks required.

---

## 🔗 Featured Links

The page serves as a link directory to the following profiles:

| Platform | Link | Description |
| :--- | :--- | :--- |
| **Blog** | [bozhigkostov.wordpress.com](https://bozhigkostov.wordpress.com) | Personal blog (online since October 2020) |
| **YouTube** | [@bozhidarkostov](https://www.youtube.com/@bozhidarkostov) | Main YouTube channel |
| **YouTube Archive** | [@qiCot](https://www.youtube.com/@qiCot) | Video archive / old videos |
| **GitHub** | [bozhidarghackakostov](https://github.com/bozhidarghackakostov) | GitHub profile and code repositories |
| **Behance** | [bozhidarGkostov](https://www.behance.net/bozhidarGkostov) | Design and creative portfolio |

---

## 📁 File Structure

```plaintext
Website @Cloudflare/
├── index.html      # Main landing page markup, links, and SVG icons
├── style.css       # External stylesheet for custom layout and styling (optional/linked)
├── script.js       # External JavaScript for dynamic behaviors (optional/linked)
├── .gitignore      # Prevents OS & editor temporary files from being tracked
└── README.md       # Project overview and documentation
```

---

## 🚀 Local Development

No build step is required. You can preview the page locally using any of the following methods:

### Option 1: Direct File Open
Double-click `index.html` or open it directly in any modern web browser.

### Option 2: Python Local Server
Run a quick local HTTP server in your terminal:

```bash
# Python 3
python3 -m http.server 8000
```
Then visit `http://localhost:8000/index.html` in your browser.

### Option 3: VS Code / IDE Live Server
If using VS Code or similar editors, right-click `index.html` and select **"Open with Live Server"**.

---

## ☁️ Deployment (Cloudflare Pages)

This project is tailored for static hosting on **Cloudflare Pages**:

1. Log into your [Cloudflare Dashboard](https://dash.cloudflare.com/).
2. Navigate to **Workers & Pages** > **Create application** > **Pages** > **Connect to Git** (or use direct upload).
3. Select your repository.
4. Set build settings:
   - **Framework preset**: `None`
   - **Build command**: *(leave empty)*
   - **Build output directory**: `/` (root directory)
5. Click **Save and Deploy**.

---

## 📝 Customization

- **Update Metadata**: Modify the `<title>` and `<meta name="description">` tags in `index.html`.
- **Add or Edit Links**: Add new `<p>` blocks within the `<section>` in `<main>` with SVG icons and destination URLs.
- **Add Styling**: Create and customize `style.css` to add typography, colors, or animations.

---

## 📄 License & Copyright

&copy; October 2026 Bozhidar "G" Kostov. All rights reserved.

