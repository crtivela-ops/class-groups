# Class Group Maker

A simple, teacher-facing page for making class groups and printing a one-page grouping sheet. There is no login, no account, and no database. Names never leave the device.

**Live site:** https://crtivela-ops.github.io/class-groups/

## How to use

1. Open the live site, or download `index.html` and open it in Chrome. It works offline as a local file.
2. Optionally add a class or period name and an assignment title.
3. Type or paste a roster (one name per line). A comma-separated list, a tab-separated list, or a column pasted from a spreadsheet also works. Blank lines are ignored, and duplicate names are dropped with a warning.
4. Choose a number, then either **Make groups of this size** or **Make this many groups**.
5. Click **Make random groups**. Leftover students are spread so group sizes stay even. You can reshuffle, add or remove a group, and rename groups.
6. Move students by dragging a name onto another group, or use the **Move to…** menu on each name (this works on a Chromebook or tablet).
7. Click **Print / Save as PDF** for a clean one-page handout. In the print dialog, choose Save as PDF and letter size.

The last roster and groups are saved in this browser on this device only. **Clear everything** wipes that saved data.

## Files

- `index.html` — the entire app. No frameworks, no CDN, and no network calls.
