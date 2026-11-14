# Caribbean Qualitative Research Lab (CQRL)

**Created by Dr. Rohan Jowallah**

**A free, offline, AI-free qualitative data analysis tool that teaches students to move from evidence to defensible findings.**

**Evidence → Coding → Literature → Inference → Interpretation → Triangulation → Write-up**

CQRL is one HTML file. It runs in any modern browser on Windows, macOS, ChromeOS, Linux or a tablet. It works without internet, needs no account and no installation, and sends nothing anywhere. Students can open it from a USB stick, a shared drive, or a Moodle course page.

> **Student Quick Guide:** [CQRL-Student-Quick-Guide.pdf](CQRL-Student-Quick-Guide.pdf), a 4-page step-by-step guide for students.

**Open it now:** **https://rj952.github.io/CaribbeanQualLab/**. Or download [`index.html`](index.html) and double-click it to use it offline.

## What students can do

| Stage | Features |
|---|---|
| **1. Evidence** | Import .txt, .docx and .csv files (one row per response) or paste text. Interviews, focus groups, observations, documents, field notes and survey responses. Participant attributes (group, site, role…). Built-in pseudonymiser that keeps existing coding intact. Tested with 100 interviews. |
| **2. Coding** | Highlight text and apply colour-coded codes. Several codes per passage. In-vivo codes from participants' own words. Keyboard shortcuts 1–9. Codebook with definitions, inclusion and exclusion rules and code types. Rename, recolour, merge and regroup codes. |
| **3. Literature** | Reference library (with RIS import and export for Zotero, Mendeley and EndNote). Link references to excerpts, codes and themes as *supports, contradicts, extends, explains, identifies a gap* or *contextualises*. Literature-to-findings matrix. The app never invents citations. |
| **4. Inference** | For every excerpt: *Why does this code fit?* (analytical defence), inference, interpretation, triangulation, a language and context note, and a memo. |
| **5. Interpretation** | Drag-and-drop theme board with a central organising concept, a narrative and a status for each theme. Negative-case tracking. Visual thematic map linking codes, themes and literature (downloadable SVG). |
| **6. Triangulation** | For each theme, evidence grouped by source type, with convergent, complementary, divergent and silent patterns. Comparison by participant group. Types of triangulation (Denzin; Patton). A triangulated interpretation field. |
| **7. Write-up** | Structured findings for each theme: claim, chosen evidence, literature, alternatives and finding. Exported to Word or Markdown with an APA-style reference list. |
| **Tools** | Retrieval with filters. Case-by-code and group-by-theme matrices. Word search with code-in-context. Word frequency. Reflexive journal. Automatic decision trail (audit trail). |
| **Learn coding first** | A 15–20 minute bridging lesson before students code: quotation → code → category → theme, why a theme is not simply a bigger category, sorting practice with feedback, the four analytical questions, a “do these codes belong together?” check that requires students to explain their reasoning, and a readiness checklist. Lecturers can require it (`?learn=require`). |
| **Guidance** | Six methodological pathways, each with phases, checklists and prompts: reflexive thematic analysis, framework analysis, qualitative content analysis, grounded theory, narrative analysis and IPA. A progress dashboard tracks the student's work. |
| **Caribbean context** | Built for low bandwidth (≈140 KB, no external files). Language notes keep Jamaican Creole and other Caribbean varieties in participants' own words and record glosses separately. Fictional Caribbean practice study included. |

## Privacy

- No AI, accounts, analytics, cookies or network requests.
- Projects are saved in the browser's own storage (IndexedDB) on the student's device. *Save backup* downloads a `.cqrl.json` file that opens on any computer.
- Backups are not encrypted. Students should store them as their ethics approval requires. See [PRIVACY.md](PRIVACY.md).

## Use in Moodle

See [MOODLE.md](MOODLE.md). In short: add it as a **File** or **URL** resource that opens in a new window. Optional URL settings (`?course=EDU6001&method=rta&hide=journal`) adapt it for a course.

## Licence and ownership

- **Community Edition:** [GNU AGPL-3.0-or-later](LICENSE). It is free to use, study, share and modify. Anyone who distributes it or offers it as a network service must share their source code under the same licence.
- **Trademarks:** the name and logo are reserved. See [TRADEMARKS.md](TRADEMARKS.md).
- **Contributions** require a signed [Contributor Licence Agreement](CLA.md), so that the copyright holder keeps full rights to the project.
- **Creative rights:** the framework, design and software are the original work of Dr. Rohan Jowallah. The licence requires every copy and every fork to keep the attribution “Created by Dr. Rohan Jowallah”. See [CREATIVE-RIGHTS.md](CREATIVE-RIGHTS.md).
- Users' research data and analyses belong to them, not to the software's author.

Copyright © 2026 Dr. Rohan Jowallah.

## Copyright and creative works

**© 2026 Dr. Rohan Jowallah. All rights reserved, except as granted by the licence.**

The following are original creative works of **Dr. Rohan Jowallah**:

| Creative work | Description |
|---|---|
| **Caribbean Qualitative Research Lab™ (CQRL™)** | The software: its code, interface, workflow and visual identity, including the Caribbean colour design, madras stripe and CQ sun badge |
| **The seven-stage analytical journey** | Evidence → Coding → Literature → Inference → Interpretation → Triangulation → Write-up |
| **The analytical-defence method** | Justifying each code, then recording inference, interpretation and triangulation as separate, traceable steps |
| **Caribbean language-preservation design** | Participants' words (including Jamaican Creole) are never altered, and glosses are kept separately |
| **Guidance and learning materials** | The *Learn coding first* bridging lesson, method pathways, prompts, the fictional Caribbean practice study and all documentation |

Dr. Rohan Jowallah asserts the moral right to be identified as the creator of these works. Every copy and every modified version must keep the attribution **“Created by Dr. Rohan Jowallah”** (an AGPL-3.0 section 7(b) additional term; see [NOTICE](NOTICE) and [CREATIVE-RIGHTS.md](CREATIVE-RIGHTS.md)).

**Cite as:** Jowallah, R. (2026). *Caribbean Qualitative Research Lab* (Version 0.1.0) [Computer software].

## Roadmap

See [ROADMAP.md](ROADMAP.md): a desktop app (Tauri), encrypted projects, Moodle LTI 1.3 with grade return, supervisor review, team coding, and optional administrator-controlled local or cloud AI in commercial editions.

## Contributing

Bug reports and ideas are welcome as GitHub Issues. Before you open a pull request, read [CONTRIBUTING.md](CONTRIBUTING.md).
