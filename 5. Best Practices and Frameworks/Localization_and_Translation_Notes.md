# 🌍 Localization and Translation Notes

Designing documentation with localization in mind ensures it can be efficiently translated into other languages without losing clarity, accuracy, or structure. This guide provides best practices to support global-ready documentation that minimizes rework and maximizes comprehension across cultures and regions.

---

## 🧠 1. Write with Translation in Mind

- Use **short, clear sentences** with one idea per sentence  
- Avoid **idioms, slang, or regional phrases** (e.g., “hit the ground running”)  
- Prefer **standard vocabulary** and avoid synonyms across sections  
- Be consistent with terminology (e.g., always use “install” not “setup”)

---

## 🏷️ 2. Use International-Friendly Formatting

| Element | Guideline |
|--------|-----------|
| **Dates** | Use full format: `August 12, 2025` or ISO `2025-08-12` |
| **Times** | Use 24-hour format (`14:00`) when possible |
| **Measurements** | Use metric by default or provide both (e.g., “25 mm (1 in)”) |
| **Currency** | Clarify: “$25 USD” instead of “$25” |
| **Numbers** | Avoid commas: use `1,000` or `1 000` based on locale |

---

## 🔡 3. Text Layout Considerations

- Avoid embedding text in **images or diagrams**
- Leave **extra white space** for translated text expansion (20–35% longer)
- For right-to-left (RTL) languages:
  - Avoid fixed alignment
  - Use mirrored icons when appropriate
  - Ensure platform supports RTL rendering

---

## 🛠️ 4. Tools & Formats that Support Localization

| Format | Consideration |
|--------|---------------|
| **Markdown** | Supports separation of text and UI references; translation-friendly |
| **HTML/XML** | Ideal with proper use of `lang` attributes and translatable tags |
| **Word (DOCX)** | Common for translation services; avoid textboxes and embedded objects |
| **PDF** | Least friendly unless source files are also provided |

---

## 🌐 5. Internationalization (i18n) Tips

- Keep UI terms and variables in **placeholders** (e.g., `Click [Install]`)  
- Separate **translatable strings** from structural code  
- If using software strings or UI-linked docs, keep ID mapping consistent across languages

---

## 📋 6. Translation Process Flow

1. Prepare source files (clean, formatted, verified)
2. Export to supported format for CAT tools (e.g., XLIFF, PO, or CSV)
3. Translate using services or tools like:
   - SDL Trados
   - Smartling
   - Lokalise
   - Crowdin
4. Review with a native-speaking SME (Subject Matter Expert)
5. Reimport and QA test all output formats

---

## 📌 Summary

Localization-ready documentation makes content globally accessible and minimizes translation headaches. By writing clearly, formatting flexibly, and planning for multilingual use from the start, you create inclusive guides that scale across borders and audiences.

