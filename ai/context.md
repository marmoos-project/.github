# 🧠 Project AI Context — Marmoos

> “Take the Monkey Onboard”  
> A playful, open-source companion for sailors — bridging tech, sea life, and community.

---

## 1. 🌊 Project Overview

**Name:** Marmoos  
**Meaning:** From *Marmouz* (“singe espiègle” in Breton) — playful, helpful, clever.  
**Mission:** Build an open, community-driven “smart sea buddy” that assists sailors with:
- Onboard energy management
- Navigation and maintenance
- Safety and communication
- Shared data & community support

**Core values:**
- 🐒 Playfulness and approachability  
- ⚙️ Open-source collaboration  
- ⚓ Autonomy and resilience  
- 🌍 Community and solidarity  

---

## 2. 🧩 Technical Stack

| Domain | Stack / Tools |
|--------|----------------|
| **Backend** | Elixir/Phoenix, PostgreSQL, REST/GraphQL APIs |
| **App** | PySide6 |
| **DevOps / Infra** | Ansible, Terraform, Kubernetes (libvirt + K8s), Caddy |
| **Energy Systems** | Solar + Wind + Alternator (12V/24V hybrid setup) |
| **Design / UX** | Nautical minimalism, blue-green palette, wave motion |
| **Data** | Telemetry, Logs, Sensors, Tokens, Map layers |

---

## 3. ⚙️ Architecture Notes

- A **dashboard** displays live vessel data, energy flow, and maintenance logs.
- Long-term goal: decentralized **“fleet intelligence” network** powered by **KNOT tokens** and open APIs.

---

## 4. 🧭 Design & Identity

**Style keywords:**  
`nautical`, `vintage instruments`, `soft light`, `dark green terminal`, `Bretagne`, `humor`, `community`, `resilience`.

**Visual symbols:**  
- Monkey mascot (pirate or sailor style)
- Waves, anchors, compass motifs
- Boat silhouette or figurehead

**Tone:**  
Friendly, curious, slightly mischievous, but technically sharp.  
Marmoos “talks like a sailor who reads engineering manuals.”

---

## 5. 🧑‍💻 Development Conventions

- **Language:** Elixir/TS preferred, Python for app and tooling  
- **Style:** Functional, minimal side-effects  
- **Infrastructure:** IaC-first (Terraform/Ansible)  
- **Tests:** Molecule for Ansible, ExUnit for Elixir  
- **Docs:** Markdown + Hugo + Mermaid diagrams  
- **Versioning:** Git, semantic commits, `version.json` in builds

---

## 6. 🤖 AI Collaboration Rules

When an AI assists on this project:

### Code-oriented AIs (e.g., Continue.dev, ChatGPT)
- Always reference this file for project context.
- Follow existing conventions before proposing architecture changes.
- Provide bilingual (EN/FR) explanations when producing docs or user-facing content.
- Keep prompts modular and reusable (see `/ai/prompts/`).

### Design-oriented AIs (e.g., Midjourney, Leonardo, Figma AI)
- Use **monkey/nautical/green-blue** theme.
- Always preserve **Marmoos identity** (open, clever, maritime).
- Avoid clutter — prefer minimal, functional visuals with soft motion or texture.
- See `/design/mascotte_600.png`

---

## 7. 🧾 Directory Structure

/ai/context.md - this file
/ai/memory.md - project decisions, design notes
/ai/prompts/* - prompts

---

## 8. 🪄 AI Prompts Index

| Purpose | File | Description |
|----------|------|-------------|
| **Code generation** | `/ai/prompts/codegen.md` | Guidelines for Continue.dev or code models |
| **Design briefs** | `/ai/prompts/design.md` | Visual/UX instructions for creative AIs |
| **Reviews** | `/ai/prompts/review.md` | Used for code or doc reviews |
| **Memory** | `/ai/memory.md` | Shared decision log between AIs |

---

## 9. 📜 Example system message (for Continue.dev)

```json
{
  "system_message": "You are collaborating on the Marmoos project — an open-source smart sea buddy. Review /ai/context.md before answering. Follow Marmoos coding and design conventions. Be concise, bilingual (FR/EN) if needed, and keep the maritime tone playful but professional."
}
```

---

## 10. ⚓ License & Collaboration

Open-source license (Apache 2.0)

Community contributions managed via Foundation or DAO structure

Tokenomics under evaluation: KNOT token for contributions & data sharing
