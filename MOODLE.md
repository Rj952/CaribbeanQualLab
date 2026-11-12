# Using CQRL in Moodle

CQRL is one self-contained HTML file. It needs no plugin and no server, and uses no bandwidth after it loads (≈140 KB).

## Option A: File resource (works on any Moodle site)
1. Download `index.html` and rename it, for example `qualitative-lab.html`.
2. In your course: **Add an activity or resource → File**, then upload it.
3. Under **Appearance → Display**, choose **In pop-up** or **New window**. Downloads (exports and backups) can be blocked inside embedded frames.
4. Students' work is saved in their own browser. They submit exports (Word report, CSV, backup) through a normal **Assignment** activity.

## Option B: URL resource (the hosted copy)
Add a **URL** resource that points to **https://rj952.github.io/CaribbeanQualLab/**. Set it to open in a new window. You can add settings to the address:

| Parameter | Effect | Example |
|---|---|---|
| `course` | Shows the course code in the header | `?course=EDRS6001` |
| `institution` | Shown on the About page | `&institution=UWI%20Open%20Campus` |
| `method` | Default approach for new projects: `rta`, `framework`, `content`, `gt`, `narrative` or `ipa` | `&method=framework` |
| `lock=1` | Together with `method`, stops students changing the approach | `&method=rta&lock=1` |
| `hide` | Hides sections (comma-separated): `literature,themes,triangulate,explore,journal,write,export` | `&hide=journal` |

Example: `https://rj952.github.io/CaribbeanQualLab/?course=EDRS6001&method=rta&lock=1`

## Suggested assessment
Ask students to submit:
1. **Full analysis report (Word)**: codebook, themes with evidence, triangulation and findings
2. **Journal and decision trail (Word)**: evidence of reflexivity and an audit trail
3. **Project backup (.cqrl.json)**: lets the lecturer open the full project in their own copy of CQRL

## Things to know
- Projects live in the browser that created them. A student who changes computer or browser must use **Save backup** and **Open backup**.
- In private or incognito windows, or where storage is blocked, a yellow banner warns students to save a backup before closing.
- A Moodle plugin and LTI 1.3 integration with central saving and grade return are planned for institutional editions. See ROADMAP.md.
