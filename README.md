# KJV Words — Milk 45 Sources

A Next.js project for **KJV Bible verses by topic and category**, drawn from the KJV-RD-milk 45 sources (Park Jin-young sermon series). Use it to share and discuss the Word in a way that fits your audience, situation, and level of Bible knowledge.

Inspired by the format and style of [kjv-faith-ai](https://github.com/henrynkoh/kjv-faith-ai).

**→ [Landing page (visual overview & navigation)](docs/index.html)** — Modern, interactive layout with a left sidebar and all contents visible. Enable GitHub Pages (Settings → Pages → Source: Deploy from branch → Branch: main, folder: /docs) to serve it as the site root.

---

## What’s in this repo

| Item | Description |
|------|-------------|
| **KJV-RD-milk45-COMBINED-REPORT.md** | Single copy-pastable report: sermon outlines and categorized verses (KJV + 흠정역 한글) for all 40 processed sources. Use it in Google Docs or elsewhere. |
| **docs/** | Manual, tutorial, and quickstarter. |
| **docs/ads/** | Ready-to-use ad copy for Facebook, Instagram, Threads, Blogger, Naver, Tistory, WordPress, newsletter, and email. |

---

## Quick start

1. **Use the combined report**  
   Open `KJV-RD-milk45-COMBINED-REPORT.md`, copy the content you need, and paste into Google Docs (or any editor). For black text on white in Google Docs: set text color to black and **File → Page setup → Page color → white**.

2. **Run the app (when the Next.js app is added)**  
   ```bash
   npm install
   npm run dev
   ```  
   Then open [http://localhost:3000](http://localhost:3000).

---

## Content overview

- **45 sources** — Transcripts from the KJV-RD-milk lecture series.
- **40 processed** — Each has a full sermon outline and Bible verses grouped by two main messages.
- **Format** — KJV verse → Korean (흠정역 한글성경전서) or a short essential message.
- **Topics** — Rightly dividing Scripture, Jewish vs Gentile era, Paul’s gospel, corporate Christ, faith, and related themes.

---

## Docs

- **[Manual](docs/MANUAL.md)** — How to use the report and (when available) the app.
- **[Tutorial](docs/TUTORIAL.md)** — Step-by-step guide to topics, categories, and workflows.
- **[Quickstarter](docs/QUICKSTARTER.md)** — Short path to get value in a few minutes.

---

## Tech (planned)

- **Next.js** — App router, React.
- **Content** — Structured by topic/category; verses without redundancy or omission.
- **Audience-aware** — Adjust depth and presentation by situation and Bible knowledge.

---

## License

See repository or project owner for terms.
