# Cordis Precept Archive
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

4. That's all. (The site is automatically rebuilt.)

- Each entry **must have** `title`, `essence`, `item`, and `layout: precept` in the frontmatter.
- The indexes automatically group by essence and item.
- Todo: Customize layout (via an a `assets/` folder with styles).
