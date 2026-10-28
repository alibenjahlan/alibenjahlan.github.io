# GitHub Pages Deployment Instructions

This directory contains the production release build of your Flutter portfolio website, configured and ready for **GitHub Pages**.

## What is Included:
- **`index.html`**: The main entry point with your metadata, SEO tags, and Tawk.to live chat.
- **`404.html`**: A copy of `index.html` ensuring GitHub Pages supports single-page routing without broken 404 pages on refresh.
- **`.nojekyll`**: Tells GitHub Pages to skip Jekyll processing so all Flutter assets, fonts, and CanvasKit WebAssembly files load properly.
- **`main.dart.js`**: Optimized, tree-shaken Flutter application bundle.
- **`resume.pdf`**: Direct CV download file.
- **`assets/`**: All images, icons, educational photos, and fonts.
- **`canvaskit/`**: High-performance CanvasKit WebAssembly renderer.

---

## How to Deploy to GitHub:

### Option 1: Direct Git Commit & Push (from `alibenjahlan.github.io`)
The files in this folder have already been automatically synced to your `d:\personal\githubprofile\new\alibenjahlan.github.io` repository. You can simply run:

```bash
cd d:\personal\githubprofile\new\alibenjahlan.github.io
git add .
git commit -m "Deploy latest portfolio build with Live Chat, CV Download, and Email"
git push origin main
```

### Option 2: Copy and Paste
1. Open this `portfolio/release` folder in File Explorer.
2. Select **all files and folders** (including hidden files like `.nojekyll`).
3. Copy them (`Ctrl + C`).
4. Paste them into the root of your GitHub Pages repository (`alibenjahlan.github.io`).
5. Commit and push to GitHub!
