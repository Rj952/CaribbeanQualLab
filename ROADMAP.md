# Roadmap and commercial model

## Principle
The **core research workflow stays free** for students: coding, literature, inference, interpretation, triangulation, write-up and export. Revenue comes from what institutions and professionals need around that core, never from locking students out of analysis.

## Editions

| Edition | Licence | Audience | Adds |
|---|---|---|---|
| **Community** (this repository) | AGPL-3.0 | Students, lecturers, independent researchers | Complete single-user analysis workflow, offline |
| **Educator** | Commercial | Lecturers and supervisors | Assignment templates, supervisor review mode with comments on excerpts and themes, rubric for analytical reasoning, cohort progress |
| **Institution** | Commercial | Universities and colleges | Moodle plugin / LTI 1.3 with central saving and grade return, SSO, admin console, licence management, deployment support, training |
| **Professional** | Commercial | Research firms, NGOs, government | Encrypted projects, team coding and merge, inter-coder comparison (where methodologically appropriate), audio and video transcripts, mixed-methods exports |
| **AI add-on** | Commercial, metered | Any paid edition | Optional AI assistance, **switched on or off by the administrator**. Local on-device models (no data leaves the device, no credits) or cloud models through a secure gateway with per-user quotas, budgets and a kill switch. API keys never ship in the app. |

## Technical path
1. **v0.x (now):** single HTML file, IndexedDB, offline, Moodle file/URL resource.
2. **v1.0:** encrypted backups (Web Crypto, passphrase), PDF import, undo history, accessibility audit, translations (Spanish, French, Haitian Kreyòl, Dutch/Papiamento).
3. **Desktop:** wrap the same app in **Tauri**: signed Windows and macOS installers, SQLite storage with FTS5 search, OS keychain encryption.
4. **Institution:** LTI 1.3 tool plus a small licensing service: entitlements, admin dashboard, central project storage options.
5. **AI gateway:** FastAPI service that authenticates users, checks entitlements and quotas, logs usage and proxies to approved models. Cloud AI requires explicit consent for each project.

## Extension seam
`window.CQRL.registerView(id, label, renderFn)` and the `cqrl:save` event let separately licensed modules add views without forking the AGPL core. Keep commercial modules in **separate repositories and files**. Do not copy community-contributed code into them unless it was received under the CLA.

## Protecting the commercial path (checklist)
- [x] AGPL-3.0 core with copyright held by one owner
- [x] CLA for all outside contributions
- [x] Trademark policy, so forks must rename
- [ ] Register the name and logo with JIPO (Jamaica Intellectual Property Office) and, later, in key markets
- [ ] Decide whether to hold IP personally or in a company, and assign it formally if a company is formed
- [ ] Written IP assignment from any paid developers or contractors
- [ ] Legal review of the CLA and any future licence terms by a Jamaican IP lawyer
- [ ] Pilot with a postgraduate cohort, using fictional or approved data, before institutional sales
