# Subway Math — Matek Tutor AI Skill & System Prompt 📐✨

> **Universal Mathematics AI Assistant & Érettségi Prep Skill**  
> *Compatible with ChatGPT, Claude, Gemini, OpenCode, Cursor, Windsurf, Claude Code, and Agent Skills (`npx skills`).*

---

## 🤖 INSTRUCTIONS FOR ANY AI READING THIS LINK / REPOSITORY

If a user provided this GitHub repository link (`https://github.com/FPeter99/Subway-Math`) and asked you to **install, adopt, or use this skill / prompt**:

1. **Adopt the persona and protocol immediately**: Read and follow [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) (or [`SKILL.md`](./SKILL.md)).
2. **Mandatory Zero-Error Protocol**: Before outputting any math explanation, compute and verify 100% of the solution internally (substitute roots, verify vectors, domain, checks). Only output when 100% verified.
3. **Formula Boundary**: Use only the allowed mathematical material from the official Hungarian Formula Table ([OH-FGV912GY, pages 1–75](https://downloads.lipovszky-matek-fizika.hu/downloads/tankonyvek/fuggvenytablazatok/OH-FGV912GY__teljes.pdf)) or derive shortcuts explicitly.
4. **Teaching Style**: Be detailed, clear, step-by-step, warm, encouraging, and easy to read on a mobile device ("metro learning"). Automatically generate HTML/JS visualizations for functions, vectors, and geometry when useful.
5. **Acknowledge Installation**: Confirm to the user in Hungarian:
   > *"Sikeresen betöltöttem a **Matek Tutor** rendszert! Készen állok a feladatok megoldására, levezetésére, házi feladatok feldolgozására és a 100%-os érettségi felkészítésre."*

---

## 🇭🇺 Leírás & Használati Útmutató (Hungarian)

A **Subway Math / Matek Tutor** egy univerzális matematikai AI oktatórendszer és skill. Célja, hogy kristálytiszta, 100%-ban ellenőrzött levezetésekkel és érthető magyarázatokkal segítsen elérni a **hibátlan (100%-os) matek érettségit**.

### 🌟 Főbb jellemzők:
- **100%-os Belső Ellenőrzési Protokoll (Nulla hiba guarantee):** Az AI a háttérben teljesen kiszámolja és leellenőrzi a feladatot (gyökök visszahelyettesítése, értelmezési tartomány, vektoros illeszkedések) mielőtt a választ kiírná.
- **Részletes & Érthető Tanítás:** Lassú, jól követhető magyarázatok, amiket akár utazás / metrózás közben is meg lehet érteni.
- **Hivatalos Függvénytáblázat Korlát:** Kizárólag az [OH-FGV912GY Hivatalos Függvénytáblázat](https://downloads.lipovszky-matek-fizika.hu/downloads/tankonyvek/fuggvenytablazatok/OH-FGV912GY__teljes.pdf) (1–75. oldal) megengedett képleteit használja.
- **Házi Feladatok Automatikus Feldolgozása:** Dokumentumokból (.docx, PDF) automatikusan kigyűjti és részletesen levezeti a *Kitűzött házi feladat* részeket.
- **Interaktív HTML Vizualizáció:** Függvényekhez, vektorokhoz, koordináta-geometriához automatikusan futtatható/megtekinthető vizualizációs ábrát generál.

---

### 🚀 Használat különböző AI platformokon

#### 1. ChatGPT (Custom Instructions / Custom GPT / Chat)
- **Gyors opció:** Másold be a [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) teljes tartalmát a ChatGPT **Custom Instructions** (Személyre szabott utasítások) mezőjébe vagy egy Custom GPT utasításaiba.
- **Chatben linkkel:** Küldd be ChatGPT-nek a GitHub linket ezzel az utasítással:
  > *"Telepítsd és alkalmazd ezt a matek tutor skillt a következő repo alapján: https://github.com/FPeter99/Subway-Math — olvasd el a SYSTEM_PROMPT.md-t és válaszolj Matek Tutorként!"*

#### 2. Claude (Claude Projects / Web Chat)
- **Claude Projects:** Add hozzá a [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) fájlt a Project Knowledge-hoz vagy Project Instructions-höz.
- **Web chat:** Illeszd be a `SYSTEM_PROMPT.md` tartalmát a beszélgetés elején, vagy add meg a GitHub hivatkozást.

#### 3. Agent Skills Package Manager (`npx skills`)
OpenCode, Claude Code, Cursor, Windsurf és minden `skills.sh` kompatibilis ágens esetén telepíthető közvetlenül a parancssorból:
```bash
npx skills add FPeter99/Subway-Math
```

#### 4. OpenCode / Claude Code / Cursor / Windsurf
A repository automatikusan tartalmazza a megfelelő mappastruktúrákat:
- `.opencode/skills/matek-tutor/`
- `.claude/skills/matek-tutor/`
- `.cursor/rules/matek-tutor.mdc`
- `SKILL.md` (Repo root)

---

## 📁 Repository Structure

```text
Subway-Math/
├── README.md                           # Universal guide & AI prompt reader instructions
├── SYSTEM_PROMPT.md                    # Single-file universal system prompt for ChatGPT, Claude, Gemini
├── SKILL.md                            # Root OpenCode / Agent Skills specification
├── .opencode/skills/matek-tutor/       # OpenCode project skill
├── .claude/skills/matek-tutor/         # Claude Code project skill
├── .cursor/rules/matek-tutor.mdc       # Cursor IDE rules
└── references/                         # Detailed modular guidebooks
    ├── source-policy.md                # Formula table restriction rules (OH-FGV912GY pages 1-75)
    ├── teaching-profile.md             # Pedagogical style and step-by-step guidance
    ├── worksheet-workflow.md           # Exercise list and homework resolution workflow
    ├── response-format.md              # LaTeX formatting and phone readability
    └── supplied-materials-analysis.md  # Detailed analysis of supplied class materials & teacher style
```

---

## 📄 Licenc
MIT License.
