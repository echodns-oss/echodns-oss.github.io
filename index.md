---
layout: default
title: Precept Archive
---

# 📜 Precept Archive

Browse by:
- [Essence](/essences)
- [Item](/items)

Or view all precepts directly:
<ul>
{% for precept in site.precepts %}
  <li><a href="{{ precept.url }}">{{ precept.title }}</a></li>
{% endfor %}
</ul>

---

## 🛠️ Build Tool
Try assembling a set of up to 8 Precepts (no duplicate Essences or Items):  
➡️ [Open Build Tool](/build)
