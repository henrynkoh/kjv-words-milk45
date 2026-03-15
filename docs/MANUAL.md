# KJV Words Milk 45 — User Manual

This manual explains how to use the combined report and (when available) the Next.js app.

---

## 1. The combined report

### What it is

- One document with **all 40 processed sources** from the KJV-RD-milk series.
- For each source: **full sermon outline** and **all Bible verses** grouped by two main messages.
- Verses are in **KJV** plus **Korean (흠정역 한글성경전서)** or a short essential message.

### Where it lives

- File: **`KJV-RD-milk45-COMBINED-REPORT.md`** in the project root.

### How to use it

1. Open `KJV-RD-milk45-COMBINED-REPORT.md` in any text editor or in Cursor/VS Code.
2. Copy the section you need (one source, one category, or the whole file).
3. Paste into Google Docs (or Word, Notion, etc.).
4. **In Google Docs:** For black text on white: select all → set text color to black; **File → Page setup → Page color → white**.

### Filling the report with content

- If the “Paste your compiled content below” section is still empty, get the compiled text from:
  - A Tailored Report in Studio/NotebookLM, or
  - Another chat/document where the 40 summaries were generated, or
  - New processing from the YouTube transcripts (you can ask the agent to process and append to the file).

---

## 2. Structure of each source in the report

Each source block has:

| Part | Description |
|------|-------------|
| **Source Title** | Video title and speaker (e.g. Park Jin-young). |
| **I. Full Sermon Outline** | Introduction and main messages (1, 2, …). |
| **II. All Bible Verses** | Two categories (two distinct messages). Under each: book chapter:verse, KJV text, then Korean or essential message. |

Use the outline for teaching flow; use the verses for study, comparison, and sharing.

---

## 3. Using verses by audience and situation

- **Beginners:** Use the outline and a few key verses per message; add Korean or essential message when helpful.
- **Group study:** Pick one source and one message; go through each verse in KJV and Korean.
- **Teaching / preaching:** Use the full outline; pull verses from both categories as needed.
- **Personal study:** Read outline → Category 1 verses → Category 2 verses; compare KJV and Korean.

---

## 4. Running the Next.js app (when added)

When the app exists in this repo:

1. Install dependencies: `npm install`
2. Start dev server: `npm run dev`
3. Open [http://localhost:3000](http://localhost:3000)
4. Use the UI to browse by topic/category and view verses (and Korean/essential message) as implemented.

The app will follow the same topic/category structure and present verses without redundancy or omission.

---

## 5. File and folder reference

| Path | Purpose |
|------|---------|
| `README.md` | Project overview and links. |
| `KJV-RD-milk45-COMBINED-REPORT.md` | Main copy-pastable report. |
| `docs/MANUAL.md` | This manual. |
| `docs/TUTORIAL.md` | Step-by-step tutorial. |
| `docs/QUICKSTARTER.md` | Quick start in a few minutes. |
| `docs/ads/` | Ad copy for social and blogs. |

---

## 6. Troubleshooting

- **Report is empty or partial**  
  Paste the full compiled content into the “Paste your compiled content below” section, or request regeneration from transcripts.

- **Formatting in Google Docs**  
  After paste, select all → set font and size if needed → text color black → File → Page setup → Page color white.

- **App not running**  
  Ensure Node.js is installed, run `npm install` in the project root, then `npm run dev`. If the app is not yet in the repo, only the report and docs are available.

For more step-by-step guidance, see **TUTORIAL.md** and **QUICKSTARTER.md**.
