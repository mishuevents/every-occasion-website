# Every Occasion Co. — Event Styling & Decor

A static one-page website (HTML + CSS + vanilla JavaScript). No framework required.

## Project structure

```
every-occasion-co/
├── index.html        # Page markup
├── css/styles.css    # All styles (colors are CSS variables at the top)
├── js/main.js        # Sticky nav + gallery filter
├── images/           # 16 photos (hero + intro + gallery)
├── package.json      # Dev server (Vite)
└── .vscode/          # Recommended extensions & settings
```

## Run it in VS Code

**Requirements:** [VS Code](https://code.visualstudio.com/) and [Node.js](https://nodejs.org/) 18 or newer.

1. Unzip the folder, then in VS Code choose **File → Open Folder…** and select `every-occasion-co`.
2. Open the terminal (**Terminal → New Terminal**) and run:

   ```bash
   npm install
   npm run dev
   ```

3. Your browser opens at `http://localhost:5173`. Edits to HTML/CSS/JS reload instantly.

### No Node.js? Use Live Server instead

1. When VS Code prompts, install the recommended extensions (or install **Live Server** by Ritwick Dey).
2. Right-click `index.html` → **Open with Live Server**.

## Build for hosting

```bash
npm run build     # outputs an optimized site to dist/
npm run preview   # preview the built site locally
```

Upload the `dist/` folder (or the project folder as-is) to any static host — Netlify, Vercel, GitHub Pages, etc.

## Notes

- Fonts (Fraunces, Manrope) load from Google Fonts, so an internet connection is needed for them to show.
- The contact form currently only shows a thank-you message; it does not send email. Connect it to a service like Formspree or Netlify Forms to receive inquiries.
- The Instagram links point to `https://instagram.com` — replace with the real profile URL.
