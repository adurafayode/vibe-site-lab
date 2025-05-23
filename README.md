# 🚀 Vibe Sites: Craft Your Digital Identity

> Part of the "Vibe Coding" Workshop Series - Create stunning personal sites with minimal effort.

AI Knowledge Series – **"Vibe Coding"** Workshop

Welcome! This repo contains **three one‑page website templates** you can customise in minutes.  
You'll use an AI‑powered editor—**Windsurf** or **Cursor**—to tweak text, colours, and layout by _prompting_ instead of hand‑coding.

---

## ⚙️ Prerequisites

- **GitHub account** – create one free at <https://github.com>
- **Windsurf _or_ Cursor** – both include built‑in AI chat for code
- **Git** – already on macOS / Linux; Windows users install **Git for Windows**

---

## 🗂 Templates

| Folder                        | Look & Feel                              | Images?                       |
| ----------------------------- | ---------------------------------------- | ----------------------------- |
| `templates/mono-card/`        | Centered card with small avatar          | **Yes** (`assets/avatar.jpg`) |
| `templates/minimal-sections/` | Clean stacked sections, small avatar bar | **Yes** (`assets/avatar.jpg`) |
| `templates/sidebar-resume/`   | Fixed sidebar résumé (text only)         | **No images**                 |

Each template folder holds:

- `index.html` – page structure
- `styles.css` – colours & layout
- `README.md` – **prompt cheat‑sheet** (copy‑paste phrases for the AI)

---

## 🚀 Quick Start

1. **Fork & Clone**

   ```bash
   # Fork this repository first, then clone your fork
   git clone https://github.com/[your-username]/vibe-site-lab.git
   cd vibe-site-lab
   ```

2. **Choose a Template**

   ```bash
   # Copy your chosen template to the root (example: minimal-sections)
   cp -r templates/minimal-sections/* .

   # Or for Windows:
   # xcopy templates\minimal-sections\* . /E /H
   ```

3. **Open & Edit**

   ```bash
   # Open in your preferred editor (we recommend Cursor)
   cursor .

   # Or just open index.html in your browser to preview
   ```

4. **Customize**
   - Replace `avatar.jpg` in the assets folder
   - Edit `index.html` to update content
   - Modify `styles.css` to adjust the design

💡 **Pro Tips:**

- Each template has its own prompt guide (e.g., `minimal-sections-prompt-guide.md`)
- Use the AI prompts section below for quick customization
- Test your site in different browsers and screen sizes

## 🗣️ Refining with AI Prompts

> Each template has its own prompt guide. Here are some common examples:

- **Replace avatar**  
  `Replace avatar.jpg with assets/[your-photo].jpg and keep class="avatar"`
- **Change name & tagline**  
  `Set the <h1> to "[Your Name]" and subtitle to "[Your Role]"`
- **Rewrite About section**  
  `Rewrite the About paragraph to highlight your experience in [field] and current focus`
- **Update colours**  
  `Change --clr-primary to [your-color] (e.g., #14b8a6) and adjust elements accordingly`
- **Customize social links**  
  `Update social buttons with your preferred contact methods`
- **Add dark mode**  
  `Add dark mode support with your preferred color scheme`

---

## 💾 Commit & Push

```bash
git add .
git commit -m "Personalised site"
git push
```

## 🌐 Deploy

### GitHub Pages

1. **Settings → Pages**
2. **Source → Deploy from a branch**
3. Branch `main`, Folder `/` (root) → **Save**
4. Wait ≈ 30 s → visit  
   `https://[your-username].github.io/vibe-site-lab/`

### Vercel (optional)

1. <https://vercel.com/import> → **Import Git Repository**
2. Keep **Root Directory = /**, **Framework = Other**
3. Click **Deploy** – Vercel returns a live URL.

---

## ❓ Troubleshooting

> **404 page?**  
> Ensure `index.html` **and** `styles.css` sit in the repo **root** and are pushed to `main`.

> **Avatar missing?**  
> File name / path mismatch, or image not committed.

> **Styles won't update?**  
> Hard‑refresh (Ctrl/Cmd + Shift + R) or clear browser cache.

---

## 📄 License

MIT © 2025 Adura
