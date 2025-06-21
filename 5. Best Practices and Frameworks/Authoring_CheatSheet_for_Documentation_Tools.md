# ⚡ Authoring Cheat Sheet for Documentation Tools

This quick-reference guide offers practical tips, syntax, and best practices for writing technical documentation across Markdown, GitHub-flavored Markdown (GFM), and Microsoft Word. Use it to streamline formatting, improve consistency, and reduce time spent troubleshooting layout issues.

---

## 📝 1. Markdown Basics

| Element | Syntax | Example |
|--------|--------|---------|
| Heading 1 | `#` | `# Installation` |
| Heading 2 | `##` | `## Step-by-Step` |
| Bold | `**text**` | **Bold** |
| Italic | `*text*` | *Italic* |
| Inline Code | `` `code` `` | `config.json` |
| Link | `[title](url)` | [Docs](https://example.com) |
| Image | `![alt](url)` | ![Logo](logo.png) |
| Bullet List | `- item` | `- Step 1` |
| Numbered List | `1. item` | `1. Open file` |
| Blockquote | `> text` | > Note this section |
| Code Block | <code>```language<br>code<br>```</code> | ```bash<br>npm install``` |

---

## 🧰 2. GitHub-Flavored Markdown (GFM)

| Feature | Tip |
|--------|-----|
| Task Lists | Use `- [ ]` and `- [x]` for checkboxes |
| Tables | Use pipes and dashes for columns |
| Emoji | Use `:emoji:` syntax (e.g., `:rocket:` 🚀) |
| Syntax Highlighting | Use code fences with language (e.g., ```js) |
| Relative Linking | `[Guide](../Install/Guide.md)` works in GitHub previews |

---

## 📄 3. Microsoft Word Formatting Tips

| Task | Steps |
|------|-------|
| Styles | Use Heading 1/2/3 to auto-generate TOC |
| Lists | Avoid manual tabs; use bullets/numbered list styles |
| Table Layout | Use AutoFit > Fixed Column Width for consistency |
| Alt Text | Right-click image > Edit Alt Text |
| Hyperlinks | Ctrl + K to insert a link |
| Accessibility | Use Review > Accessibility Checker before publishing |

---

## 🧩 4. Conversion Tools

| Goal | Tool |
|------|------|
| Markdown → PDF | [Pandoc](https://pandoc.org/) or VS Code extensions |
| Word → Markdown | [Word2MD](https://word2md.com/) or Pandoc |
| Markdown → HTML | Static site generators (e.g., MkDocs, Docusaurus) |
| Multi-format publishing | MadCap Flare, Adobe FrameMaker |

---

## 📋 5. Keyboard Shortcuts (Quick Highlights)

| Tool | Shortcut | Action |
|------|----------|--------|
| Word | Ctrl + Alt + 1/2/3 | Apply Heading 1/2/3 |
| Word | Ctrl + K | Insert Hyperlink |
| VS Code | Ctrl + B / `**` | Bold (Markdown preview plugin) |
| GitHub | `b` | Browse files quickly |
| GitHub | `t` | File finder |

---

## 📌 Summary

This cheat sheet provides a fast reference for authoring high-quality documentation using the most common tools. Keep it handy during editing or formatting reviews to stay efficient and aligned with documentation standards.
