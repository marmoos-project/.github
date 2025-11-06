# 🧠 Shared Memory — Marmoos Project

> This file captures *decisions*, *insights*, and *context updates*  
> that all AIs should read before generating new outputs.

---

## 🔄 Last Context Sync
*Updated:* {{date auto}}

---

## ✅ Key Decisions

| Date | Topic | Decision | Notes |
|------|--------|-----------|-------|
| 2025-11-05 | Repo layout | All AI assets live under `/ai/` | Unified context folder |
| 2025-11-05 | Visual style | Blue-green maritime palette, minimalist icons | Wave & monkey recurring |
| 2025-11-05 | Energy monitoring | CAN/NMEA2000 primary, MQTT bridge secondary | ESP32 + Nerves |
| 2025-11-05 | K8s setup | Local libvirt cluster via Terraform + Kubespray | Development baseline |

---

## 🧩 Open Topics / TODO

- [ ] Tokenomics model (KNOT reward + governance)
- [ ] Foundation vs. fund-of-donations structure
- [ ] Add bilingual user documentation templates
- [ ] Define visual identity variations (dark/light themes)

---

## 💬 Design References

- **Typography:** Vintage LCD/monospace + soft serif combo  
- **Color palette:**  
  - Deep navy `#001F2B`  
  - Algae green `#1C7C64`  
  - Warm sand `#E3CBAA`  
- **Mood:** calm, reliable, maritime tech

---

## 📚 Resources

- Diagrams: `/docs/architecture.md`, `/docs/energy-system.md`
- Logo assets: `/design/marmoos_logo.svg`
- Tokenomics draft: `/docs/knot_whitepaper.md`

---

## ⚙️ AI Usage Note

Any AI or agent joining the project must:
1. Read `/ai/context.md`
2. Read the latest `/ai/memory.md`
3. Append summary of any new decisions made.

Example update:
```markdown
### [2025-11-07] — Added new Ansible Molecule scenario for energy sensors
Reason: test automation on simulated CAN devices.
```


---

## 🤖 `/ai/prompts/codegen.md`

```markdown
# ⚙️ Marmoos Codegen Prompt Template

**Use this when writing or refactoring code via Continue.dev, ChatGPT, or other coding AIs.**

---

## 🧭 Goal
Generate **maintainable, production-ready** code that fits Marmoos’ embedded + cloud ecosystem.

---

## 🧩 Context Summary
See `/ai/context.md` for project overview and conventions.

Key expectations:
- Functional and fault-tolerant design (Elixir/Erlang mindset)
- Small composable modules
- Follow naming conventions: `marmoos_*` prefix for core libs
- Prefer declarative IaC (Ansible/Terraform)

---

## 📋 Prompt Template

```raw
You are a senior Marmoos developer.
Generate or refactor code based on the following input.

Context:
{{brief description of module}}

Constraints:

Conform to Marmoos conventions from /ai/context.md

Provide inline comments in English

Output bilingual docstrings (FR/EN)

Include test stubs when appropriate
```


---

## 🧱 Output Format

File: path/to/file.ex
<code>
Tests
<code>
Notes

<explanation in EN/FR>

---

## ⚠️ Quality Checks

Before committing generated code:
- ✅ Syntax passes linter (`mix format`, `eslint`, etc.)
- ✅ No hardcoded secrets or paths
- ✅ Comments explain reasoning briefly
- ✅ Reuses existing functions when possible

---
