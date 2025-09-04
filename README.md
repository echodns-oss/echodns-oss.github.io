# Precept Archive

A lightweight Jekyll site for hosting your Precepts on GitHub Pages.

## 🚀 Setup

1. **Create a new GitHub repository** (public or private).
2. Upload the contents of this folder (or unzip and `git push`).
3. In your repo, go to **Settings > Pages**, and set:
   - Source: `main` branch
   - Folder: `/ (root)`
4. Your site will be live at `https://<username>.github.io/<repository>/`.

## 📜 Adding Precepts

1. Go to the `_precepts/` folder.
2. Create a new `.md` file, e.g. `mystic-lantern.md`.
3. Use this template:

```yaml
---
title: Mystic Lantern
essence: Light
item: Lantern
layout: precept
---

A lantern filled with captured starlight. Its glow banishes shadows and reveals hidden truths.
```

4. Commit and push — the site will rebuild automatically.

## 📂 File Structure

- `_precepts/` → one Markdown file per Precept (with YAML metadata).
- `_layouts/` → Jekyll HTML templates for rendering.
- `index.md` → Landing page with navigation.
- `essences.md` → Auto-generated list of Precepts by Essence.
- `items.md` → Auto-generated list of Precepts by Item.

## ✅ Notes

- Each Precept **must have** `title`, `essence`, `item`, and `layout: precept` in the frontmatter.
- The indexes automatically group by essence and item — no need to update them manually.
- You can customize layout and CSS if desired (add a `assets/` folder with styles).

---

Happy worldbuilding!
