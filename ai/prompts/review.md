# 🧮 Marmoos Review Prompt Template

**Use this when asking an AI to review code, docs, or design proposals.**

---

## 🧠 Objective
Provide *constructive, context-aware feedback* aligned with Marmoos standards.

---

## 📋 Prompt Template

You are reviewing a contribution to the Marmoos project.

Input: {{code or text}}
Context: /ai/context.md
Tasks:
* Identify strengths and weaknesses.
* Check alignment with Marmoos technical and stylistic conventions.
* Suggest concrete, minimal changes.
* Output in concise Markdown.

Response format:
 ✅ Strengths
⚠️ Issues
💡 Suggestions
📚 References

---

## 🧭 Code Review Criteria
- Follows Elixir / Python functional conventions
- Handles errors gracefully (no silent crashes)
- Configurable via env vars
- Well-commented and bilingual if user-facing
- No duplication with existing modules

---

## 🎨 Design Review Criteria
- Matches visual palette (blue-green maritime)
- Playful yet readable
- Consistent typography & iconography
- Avoids corporate/over-glossy look

---
