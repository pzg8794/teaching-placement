# 🧭 Workspace Rules Notes

**Color Code:** ⚫ Workspace Rules

> **📌 What This Is:** Canonical rules for organizing, editing, and committing work in this teaching-placement repository.
> **🧭 Start Here When:** You are about to reorganize files, update lessons, rename folders, or make Git changes.
> **🎯 Main Goal:** Keep one clean canonical workspace with no duplication, no broken links, and no branch confusion.

---

## 📍 Non-Negotiables

- Work on the existing branch only unless the user explicitly asks for a new branch.
- Commit and push are part of the process after meaningful completed work.
- Do not create duplicate share trees or copied "shared/private" versions of the same content.
- Use the real canonical folder or file when sharing; do not duplicate content for sharing.
- After any move or rename, update Markdown links and verify they resolve.

---

## 🗂️ Directory Rules

- [pine-brook-elementary](./pine-brook-elementary/pine-brook-elementary-notes.md) holds Pine Brook placement materials.
- [pine-brook-elementary/lessons](./pine-brook-elementary/lessons/lessons-notes.md) is the canonical lesson tree.
- Each real lesson lives inside its grade folder.
- A lesson folder itself should contain the lesson packet files directly:
  - `.md`
  - `.tex`
  - `.pdf`
  - `.bib`
- Transcript source records live in [transcripts](./transcripts/transcripts-notes.md).
- Workbook files and workbook Markdown captures live in [pine-brook-elementary/teaching-placement-ignite-curriculum-gcsd-25-26](./pine-brook-elementary/teaching-placement-ignite-curriculum-gcsd-25-26/teaching-placement-ignite-curriculum-gcsd-25-26-notes.md).
- Avoid empty directories and avoid placeholder directories that do not carry real value.

---

## 📝 Markdown Rules

- Markdown should be neurodivergent-friendly by default unless the document has an external formal constraint.
- Prefer:
  - strong headings
  - icons with stable meaning
  - short sections
  - quick-scan blocks
  - visible clickable links
- Keep file names lowercase and hyphenated where practical.
- Folder notes should act as clear hubs, not vague placeholders.

---

## 🔗 Link Rules

- Use clickable local Markdown links for important files and hubs.
- After reorganizing files, check for broken links across the repo.
- Lesson files should reference the workbook note, schedule, transcripts, and evidence when relevant.
- Workbook notes should link back into lesson guides and grade guides.

---

## 🧪 Verification Rules

- After structural edits, verify local Markdown links resolve.
- Check Git status before committing so moves are tracked cleanly.
- Keep the repo readable on GitHub, not only locally.

---

## 🤝 Workflow Rules For Future Agents

- Do not improvise parallel directory systems.
- Do not create extra branches "just in case."
- Do not leave partial reorganizations uncommitted after the user asks for the work to be completed.
- Prefer one canonical source of truth for each item.
- If the user creates a folder to organize a document family, preserve that intent and update references around it.
