# 🎨 AI Tools for Front-end & UI Development

**A curated, searchable directory of 500+ AI tools** for every stage of front-end and UI work.

[![🚀 View Live Demo](https://img.shields.io/badge/🚀_View_Live_Demo-7c5cff?style=for-the-badge&logoColor=white)](https://sayedrafeeq.github.io/awesome-ai-frontend-tools.github.io/)

![514+ tools](https://img.shields.io/badge/Tools-514%2B-7c5cff?style=for-the-badge)
![16 categories](https://img.shields.io/badge/Categories-16-38d9c0?style=for-the-badge)
![MIT license](https://img.shields.io/badge/License-MIT-ffb454?style=for-the-badge)
![PRs welcome](https://img.shields.io/badge/PRs-Welcome-ff6b9d?style=for-the-badge)

![status](https://img.shields.io/badge/Status-Actively%20maintained-brightgreen?style=flat-square)
![zero dependencies](https://img.shields.io/badge/Zero%20dependencies-single%20HTML%20file-blue?style=flat-square)
![made with love](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red?style=flat-square)

[🧭 Categories](#categories) · [✨ Features](#features) · [⚡ Quick start](#quick-start) · [🛠️ Edit tools](#how-to-add-or-edit-tools) · [🙌 Submit a tool](#submit-a-tool)

---
[![AI-Tools-Poster.png](https://i.postimg.cc/Kcdp9NBT/AI-Tools-Poster.png)](https://postimg.cc/pyJBrK0V)]
---

## 🧭 What this is

One clean, self-contained HTML file that lists **514 AI tools** across **16 categories**, each with a description, pricing tier, tags, and a direct link to the official site.

- 🔍 **Live search** and 🏷️ **category filters** — no build, no server, no dependencies.
- 💰 **Pricing badges** — Free · Freemium · Paid · Open source.
- 📱 **Responsive dark theme** that works on desktop and mobile.

---

## 🧭 Categories

![Code Assistants](https://img.shields.io/badge/Code%20Assistants-35-8ea2ff?style=flat-square)
![UI & App Generation](https://img.shields.io/badge/UI%20%26%20App%20Generation-42-7ce7ff?style=flat-square)
![Design-to-Code](https://img.shields.io/badge/Design--to--Code-25-c7a7ff?style=flat-square)
![Image Generation](https://img.shields.io/badge/Image%20Generation-42-ffb454?style=flat-square)
![Video & Animation](https://img.shields.io/badge/Video%20%26%20Animation-28-ffa36b?style=flat-square)
![3D & Avatar](https://img.shields.io/badge/3D%20%26%20Avatar-19-c9a0ff?style=flat-square)
![Prototyping](https://img.shields.io/badge/Prototyping-19-38d9c0?style=flat-square)
![Component Libraries](https://img.shields.io/badge/Component%20Libraries-62-ff8fb3?style=flat-square)

![CSS & Styling](https://img.shields.io/badge/CSS%20%26%20Styling-33-8fd3ff?style=flat-square)
![Icons & Assets](https://img.shields.io/badge/Icons%20%26%20Assets-33-ffd06b?style=flat-square)
![Testing & QA](https://img.shields.io/badge/Testing%20%26%20QA-40-7bf0a8?style=flat-square)
![AI Models & SDKs](https://img.shields.io/badge/AI%20Models%20%26%20SDKs-42-ff8a8a?style=flat-square)
![Design & Collab](https://img.shields.io/badge/Design%20%26%20Collab-21-a3e26b?style=flat-square)
![Color, Type & Copy](https://img.shields.io/badge/Color%2C%20Type%20%26%20Copy-19-7ee0ff?style=flat-square)
![Dev Tools & Build](https://img.shields.io/badge/Dev%20Tools%20%26%20Build-29-ff9d6b?style=flat-square)
![Analytics & Docs](https://img.shields.io/badge/Analytics%20%26%20Docs-25-b7a6ff?style=flat-square)

| # | Category | Tools |
|---|----------|-------|
| 1 | 🧑‍💻 Code Assistants | 35 |
| 2 | 🪄 UI & App Generation | 42 |
| 3 | 🧩 Design-to-Code | 25 |
| 4 | 🖼️ Image Generation | 42 |
| 5 | 🎬 Video & Animation | 28 |
| 6 | 🧊 3D & Avatar | 19 |
| 7 | 📐 Prototyping | 19 |
| 8 | 🧱 Component Libraries | 62 |
| 9 | 🎨 CSS & Styling | 33 |
| 10 | 🧿 Icons & Assets | 33 |
| 11 | ✅ Testing & QA | 40 |
| 12 | 🤖 AI Models & SDKs | 42 |
| 13 | 🤝 Design & Collab | 21 |
| 14 | 🌈 Color, Type & Copy | 19 |
| 15 | 🔧 Dev Tools & Build | 29 |
| 16 | 📊 Analytics & Docs | 25 |

---

## ✨ Features

| Feature | Detail |
|---------|--------|
| 🔍 **Live search** | Matches tool name, category, description, and tags |
| 🏷️ **Category filters** | One-click chips with per-category counts |
| 💰 **Pricing badges** | Free · Freemium · Paid · Open source |
| 📱 **Responsive** | Dark theme, adapts to desktop and mobile |
| ⚡ **Zero dependencies** | CSS + JS + data all inline in one HTML file |
| ♿ **Accessible** | Semantic markup, labeled search, keyboard-reachable, `lang="en"` |
| 🔗 **Direct links** | Every card links to the official site |

---

## ⚡ Quick start

No build step or dependencies required — just open the file:

```bash
# Option 1 — open directly (double-click works too)
start index.html      # Windows
open index.html       # macOS
xdg-open index.html   # Linux

# Option 2 — serve with any static server
python -m http.server 8000
# then visit http://localhost:8000/
```

---

## 📁 Repository structure

```
.
├── index.html     # The list — 514 tools (self-contained)
├── nginx.conf     # Static hosting config (Function Compute / nginx)
├── LICENSE        # MIT license
└── README.md      # This file
```

> 💡 `nginx.conf` is only needed for the Function Compute `nginx` environment. For GitHub Pages or any static host, `index.html` alone is enough.

---

## 🛠️ How to add or edit tools

All data lives in a single `const TOOLS = [...]` array at the bottom of `index.html` (inside the `<script>` block). Each entry has this shape:

```js
{
  name: "Tool Name",   // required
  cat: "Category",     // must match a CAT_COLORS key
  tier: "freemium",    // free | freemium | paid | open
  desc: "Short one-line description.",
  tags: ["tag one", "tag two"],
  url: "https://example.com"
}
```

To add a tool, copy an existing entry, edit the fields, and save — the page re-renders automatically. 🎉

- **Category colors** → the `CAT_COLORS` object (same `<script>` block)
- **Hero copy / title** → the `<section class="hero">` block and the `<title>` tag
- **Footer disclaimer** → the `<footer>` block
- **Theme colors / fonts** → the `:root` CSS variables in the `<style>` block
- **Search placeholder** → the `#search` input's `placeholder` attribute

---

## 🙌 Submit a tool

Found something missing? Contributions are welcome!

1. 🍴 **Fork** this repository
2. ✏️ Add your tool to the `TOOLS` array in `index.html`
3. 📦 Open a **Pull Request**

[![Contribute](https://img.shields.io/badge/Contribute-Add%20a%20tool-7c5cff?style=for-the-badge)](https://github.com)
[![Star](https://img.shields.io/badge/Star%20this%20repo-%E2%AD%90-ffb454?style=for-the-badge)](https://github.com)

---

## ⚠️ Disclaimer

Pricing tiers and feature sets are a general snapshot and may change over time. Always verify the current plans on each product's official site before purchasing. Product names and logos belong to their respective owners.

---

## 📄 License

Released under the [MIT License](./LICENSE) — feel free to use and adapt this list. Attribution is appreciated but not required.

  Made with ❤️ for the design & code community
