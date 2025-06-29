# 🧭 Doc Team Internal Guide

This internal guide serves as the central operational reference for technical documentation teams working on installation and user guide projects. It outlines style standards, review workflows, collaboration protocols, and maintenance strategies to ensure consistent, high-quality output.

---

## 📝 1. Writing Standards

- Use **second-person voice** (“you”) and active voice for clarity.
- Follow a consistent sentence structure: *Action → Context → Result*.
- Use bulleted lists and tables to support scannability.
- Spell out acronyms on first use.
- Keep titles concise and formatted using sentence case.

---

## 🎨 2. Style & Formatting Conventions

| Element | Convention |
|--------|------------|
| File Naming | `kebab-case` (e.g., `install-solidworks-windows.md`) |
| Headings | `# Title`, `## Section`, `### Subsection` |
| Emphasis | Use `**bold**` for UI elements and *italics* for concepts |
| Code Blocks | Use fenced code blocks (```), with syntax highlighting if applicable |
| Links | Prefer relative paths for internal links, full URLs for external sources |

---

## 🔁 3. Review & Approval Workflow

1. **Drafting:** Assigned writer creates `.md` draft in staging branch.
2. **Peer Review:** Assigned teammate reviews for clarity, grammar, and structure.
3. **SME Review (if needed):** Subject Matter Expert verifies accuracy.
4. **Final Edit:** Editor formats content for publishing (TOC, file links).
5. **Publish:** Merged into `main` branch and optionally version-tagged.

---

## 👥 4. Collaboration Guidelines

- Use pull requests for all edits to main documentation.
- Always include a description of the change and affected files.
- Tag reviewers using `@` mentions in PRs.
- Use issue templates for new feature documentation requests.

---

## 🛠️ 5. Maintenance Schedule

| Task | Frequency | Owner |
|------|-----------|-------|
| Review outdated screenshots | Quarterly | Assigned writer |
| Check dead links | Bi-annually | Repo admin |
| Archive deprecated docs | As needed | Documentation manager |
| Update glossary and index | After major release | Assigned reviewer |

---

## 🔒 6. Internal File Repository

Use this structure for team-only references:

```
Internal_Resources/
├── Style_Guides/
│   └── internal-voice-tone.md
├── Reviews/
│   └── peer-review-checklist.md
├── Templates/
│   └── guide-template.md
├── Meeting_Notes/
│   └── doc-team-weekly-sync.md
```

---

## 📌 Notes

- For one-off style decisions, document your choice in `Style_Guides/`.
- For troubleshooting guides, follow the established resolution format from `Common_Error_Messages_and_Resolutions.md`.

