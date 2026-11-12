# Contributing

Thank you for helping improve the Caribbean Qualitative Research Lab.

## Before you start
- **Sign the CLA.** Every pull request needs the CLA statement from [CLA.md](CLA.md) in its description. This keeps the project able to stay free for students *and* be licensed commercially to institutions, which is how its long-term development is funded.
- **Never include real research data**, transcripts, participant names or student work in issues, pull requests or test files.
- For large changes, open an Issue first to discuss the idea.

## Design principles
1. **The researcher interprets; the software organises.** The Community Edition must never generate codes, interpretations or citations for the user.
2. **Never lose the chain of evidence:** participant words → code → literature → inference → interpretation → finding.
3. **Never alter participants' words.** This includes Creole and other language varieties.
4. **Low bandwidth first.** One HTML file, no external requests, no frameworks, no build step. It must work offline from a USB stick.
5. **Accessible.** Keyboard operable, labelled controls, sufficient contrast, readable on a phone.
6. **Method-aware.** Do not impose one procedure on all methodologies (for example, inter-coder agreement is not a quality marker in reflexive thematic analysis).

## Code
- Everything lives in `index.html`. Keep the SPDX header.
- Escape all user content with `esc()` before inserting it into HTML.
- Bump `APP.version` and keep backups backward compatible. `normalize()` must open older `.cqrl.json` files.
- Test with the built-in practice study and with a large project (100 sources).

## Licence
By contributing, you agree that your contribution is licensed as described in the CLA.
