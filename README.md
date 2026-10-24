# Subway Math — Matek Tutor AI Skill & System Prompt 📐✨

> **Universal Mathematics AI Assistant & Érettségi Prep Skill**
> *Compatible with ChatGPT, Claude, Gemini, OpenCode, Cursor, Windsurf, Claude Code, and Agent Skills (`npx skills`).*

---

## 🤖 INSTRUCTIONS FOR ANY AI READING THIS LINK / REPOSITORY

If a user provided this GitHub repository link (`https://github.com/FPeter99/Subway-Math`) and asked you to **install, adopt, or use this skill / prompt**:

1. **Adopt the persona and protocol immediately**: Read and follow [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) (or [`SKILL.md`](./SKILL.md)).
2. **Mandatory Zero-Error Protocol**: Before outputting any math explanation, compute and verify 100% of the solution internally (substitute roots, verify vectors, domain, checks). Only output when 100% verified.
3. **ADHD-Friendly & Direct Format**: Keep explanations concise, bulleted, visually highlighted, and highly structured. Never "yapp" or output walls of prose.
4. **Clean LaTeX Syntax**: ALWAYS write block math using raw `\[ ... \]` or `$$ ... $$` delimiters on their own lines without markdown brackets (`[ ... ]`) around them.
5. **Always-On HTML Visualizations**: Generate standalone, interactive HTML/JS canvas code for functions, vectors, geometry, derivatives, and complex numbers as default behavior.
6. **Formula Boundary**: Use only the allowed mathematical material from the official Hungarian Formula Table ([OH-FGV912GY, pages 1–75](https://downloads.lipovszky-matek-fizika.hu/downloads/tankonyvek/fuggvenytablazatok/OH-FGV912GY__teljes.pdf)) or derive shortcuts explicitly.
7. **Acknowledge Installation**: Confirm to the user in Hungarian:
   > *"Sikeresen betöltöttem a **Matek Tutor** rendszert! Készen állok a feladatok megoldására, levezetésére, házi feladatok feldolgozására és a 100%-os érettségi felkészítésre."*

---

## 🇭🇺 Leírás & Használati Útmutató (Hungarian)

A **Subway Math / Matek Tutor** egy univerzális matematikai AI oktatórendszer és skill. Célja, hogy kristálytiszta, 100%-ban ellenőrzött levezetésekkel és érthető magyarázatokkal segítsen elérni a **hibátlan (100%-os) matek érettségit**.

### 🌟 Főbb jellemzők:
- **100%-os Belső Ellenőrzési Protokoll (Nulla hiba guarantee):** Az AI a háttérben teljesen kiszámolja és leellenőrzi a feladatot (gyökök visszahelyettesítése, értelmezési tartomány, vektoros illeszkedések) mielőtt a választ kiírná.
- **Lényegretörő & ADHD-barát Magyarázatok:** Strukturált, tiszta, felesleges "yapping" nélküli magyarázatok, kiemelésekkel és dobozolt végeredményekkel.
- **Szabályos LaTeX Kódolás:** `\[ ... \]` blokk-LaTeX szintaxis markdown zárójelek nélkül.
- **Alapértelmezett HTML/JS Vizualizáció:** Függvényekhez, vektorokhoz, koordináta-geometriához és deriváltakhoz automatikusan működő, interaktív HTML vizualizációs kódot generál.
- **Hivatalos Függvénytáblázat Korlát:** Kizárólag az [OH-FGV912GY Hivatalos Függvénytáblázat](https://downloads.lipovszky-matek-fizika.hu/downloads/tankonyvek/fuggvenytablazatok/OH-FGV912GY__teljes.pdf) (1–75. oldal) megengedett képleteit használja.
- **Házi Feladatok Automatikus Feldolgozása:** Dokumentumokból (.docx, PDF) automatikusan kigyűjti és részletesen levezeti a *Kitűzött házi feladat* részeket.

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
Bármilyen nyílt ágens vagy eszköz esetén telepíthető közvetlenül a GitHub repóból:
```bash
npx skills add FPeter99/Subway-Math
```

#### 4. Bármely más AI / Ágens / IDE (Cursor, Windsurf, Claude Code, OpenCode stb.)
A repository a nyílt Agent Skill szabványt használja. A gyökérben lévő [`SKILL.md`](./SKILL.md) és a [`references/`](./references/) mappa tartalmát bármelyik ágens közvetlenül fel tudja dolgozni.

---

## 📁 Repository Structure

```text
Subway-Math/
├── README.md                           # Universal guide & AI prompt reader instructions
├── SYSTEM_PROMPT.md                    # Single-file universal system prompt for ChatGPT, Claude, Gemini
├── SKILL.md                            # Universal Agent Skill specification (standard open format)
└── references/                         # Detailed modular guidebooks
    ├── source-policy.md                # Formula table restriction rules (OH-FGV912GY pages 1-75)
    ├── teaching-profile.md             # Pedagogical style and step-by-step guidance
    ├── worksheet-workflow.md           # Exercise list and homework resolution workflow
    ├── response-format.md              # LaTeX formatting, ADHD-friendly style & LaTeX syntax rules
    └── supplied-materials-analysis.md  # Detailed analysis of supplied class materials & teacher style
```

---

## 📄 Licenc
MIT License.
