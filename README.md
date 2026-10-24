# Subway Math — Matek Tutor AI Skill & System Prompt 📐✨

> **Universal Mathematics AI Assistant & Érettségi Prep Skill**
> *Compatible with ChatGPT, Claude, Gemini, OpenCode, Cursor, Windsurf, Claude Code, and Agent Skills (`npx skills`).*

---

## 🤖 INSTRUCTIONS FOR ANY AI READING THIS LINK / REPOSITORY

If a user provided this GitHub repository link (`https://github.com/FPeter99/Subway-Math`) and asked you to **install, adopt, or use this skill / prompt**:

1. **Adopt the persona and protocol immediately**: Read and follow [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) (or [`SKILL.md`](./SKILL.md)).
2. **Mandatory Zero-Error Protocol**: Before outputting any math explanation, compute and verify 100% of the solution internally (substitute roots, verify vectors, domain, checks). Only output when 100% verified.
3. **ADHD-Friendly & Direct Format**: Keep explanations concise, bulleted, visually highlighted, and highly structured. Never "yapp" or output walls of prose.
4. **Clean Math Formatting (No Broken LaTeX)**: ALWAYS write block math using standard `$$ ... $$` on separate lines. NEVER wrap equations in literal `[ ... ]` brackets or use fragile macros (`\overbrace`, `\underbrace`, `\qquad`) that break chat renderers.
5. **Mandatory Automatic HTML Visualizations**: ALWAYS generate a standalone, interactive HTML/JS canvas visualization code block in EVERY response without waiting for the user to ask for it.
6. **Formula Boundary**: Use only the allowed mathematical material from the official Hungarian Formula Table ([OH-FGV912GY, pages 1–75](https://downloads.lipovszky-matek-fizika.hu/downloads/tankonyvek/fuggvenytablazatok/OH-FGV912GY__teljes.pdf)) or derive shortcuts explicitly.
7. **Acknowledge Installation**: Confirm to the user in Hungarian:
   > *"Sikeresen betöltöttem a **Subway Math** rendszert! Készen állok a feladatok megoldására, levezetésére, házi feladatok feldolgozására és a 100%-os érettségi felkészítésre."*

---

## 🇭🇺 Leírás & Használati Útmutató (Hungarian)

A **Subway Math** egy univerzális matematikai AI oktatórendszer és skill. Célja, hogy kristálytiszta, 100%-ban ellenőrzött levezetésekkel és érthető magyarázatokkal segítsen elérni a **hibátlan (100%-os) matek érettségit**.

### 🌟 Főbb jellemzők:
- **100%-os Belső Ellenőrzési Protokoll (Nulla hiba guarantee):** Az AI a háttérben teljesen kiszámolja és leellenőrzi a feladatot (gyökök visszahelyettesítése, értelmezési tartomány, vektoros illeszkedések) mielőtt a választ kiírná.
- **Lényegretörő & ADHD-barát Magyarázatok:** Strukturált, tiszta, felesleges "yapping" nélküli magyarázatok, kiemelésekkel és dobozolt végeredményekkel.
- **Tiszta & Törhetetlen Math Formázás:** Szabályos `$$ ... $$` blokk-szintaxis. Tilos a törött `[ \begin{aligned} ... ]` zárójelezés vagy a böngészős megjelenítőt összetörő `\overbrace`, `\underbrace`, `\qquad` LaTeX makrók használata.
- **Automatikus HTML/JS Vizualizáció:** Minden válaszban automatikusan generál egy önálló, interaktív HTML vizualizációs kódot (Canvas/SVG), anélkül, hogy a felhasználónak külön kérnie kellene.
- **Hivatalos Függvénytáblázat Korlát:** Kizárólag az [OH-FGV912GY Hivatalos Függvénytáblázat](https://downloads.lipovszky-matek-fizika.hu/downloads/tankonyvek/fuggvenytablazatok/OH-FGV912GY__teljes.pdf) (1–75. oldal) megengedett képleteit használja.
- **Házi Feladatok Automatikus Feldolgozása:** Dokumentumokból (.docx, PDF) automatikusan kigyűjti és részletesen levezeti a *Kitűzött házi feladat* részeket.

---

### 🚀 Használat különböző AI platformokon

#### 1. ChatGPT (Custom Instructions / Custom GPT / Chat)
- **Gyors opció:** Másold be a [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md) teljes tartalmát a ChatGPT **Custom Instructions** (Személyre szabott utasítások) mezőjébe vagy egy Custom GPT utasításaiba.
- **Chatben linkkel:** Küldd be ChatGPT-nek a GitHub linket ezzel az utasítással:
  > *"Telepítsd és alkalmazd ezt a matek tutor skillt a következő repo alapján: https://github.com/FPeter99/Subway-Math — olvasd el a SYSTEM_PROMPT.md-t és válaszolj Matek Tutorként!"*

#### 2. Claude (Claude Projects / Web Chat / Claude Code)
- **Claude Web:** A Project Knowledge-be töltsd fel a `SYSTEM_PROMPT.md`-t.
- **Claude Code CLI:** Automatikusan felismeri a repóban található `SKILL.md`-t.

#### 3. Agent CLI / OpenCode / Cursor / Windsurf
- Telepítsd közvetlenül a hivatalos csomagkezelővel:
  ```bash
  npx skills add FPeter99/Subway-Math
  ```
