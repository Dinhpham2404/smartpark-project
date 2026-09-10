# Weekly Update Guide

The whole point of this file: every week should take about 30 minutes, and the end of the semester should take zero extra formatting work.

## The one rule

**There is one document: `Smart_Parking_Platform_Project_Document.docx`.**
Never start a second file. Never make a "week 3" copy. Open the same file, add to it, save it, upload it. That is it.

The header, footer, page numbers, and table of contents are already built in. As long as you follow Step 2 below, they keep working by themselves.

---

## Every week, do these 6 steps

### Step 1 — Open the document and add the new section
Add the new content at the right place in the document, not at the bottom. Sections are numbered, so a new "Work Breakdown Structure" section becomes Section 5, and "Next Steps" and "References" move down.

### Step 2 — Use the built-in Heading styles (this is the important one)
When you type a new section title, highlight it and pick a style from the Home ribbon:

- Main section title (like "5. Work Breakdown Structure") → **Heading 1**
- Subsection (like "5.1 Deliverables") → **Heading 2**
- Sub-subsection (like "5.1.1 Phase One") → **Heading 3**

Do **not** just make the text big and bold. If you do, it will not show up in the table of contents and you will have to fix it later.

*Check: click in your new heading. The style box on the Home ribbon should say "Heading 1", not "Normal".*

### Step 3 — Update the table of contents
Right-click anywhere on the table of contents → **Update Field** → **Update entire table** → OK.

*Check: your new section appears in the list with the right page number.*

### Step 4 — Update the Document Control table on page 1
Add one new row. Bump the version number.

| Version | Date | Author | Summary of changes |
|---|---|---|---|
| 1.0 | 2026-09-10 | D. Pham | Initial release... |
| 1.1 | *(next week's date)* | D. Pham | *(what you added)* |

The professor's slide says "**Update version** every week." This row is how you prove you did.

### Step 5 — Save, then upload to GitHub
Save the file with the same name. On GitHub: **Add file → Upload files → drag it in → Commit changes.**

GitHub keeps every old version automatically, so you can never lose last week's work.

*Check: the repo's file list shows the commit time as "now".*

### Step 6 — Record the video and submit
1–2 minutes on what is new this week. Record in MS Stream.
On Canvas, submit **two links**: the public GitHub repo URL, and the Stream video URL.

---

## Adding an image with a caption

The project brief requires image captions in the final document. Do it right the first time and there is nothing to fix later.

1. Save the image into the `figures/` folder in the repo (so you don't lose it).
2. In Word: **Insert → Pictures** and place the image.
3. Right-click the image → **Insert Caption**.
4. Leave the label as "Figure", type a short description, click OK.

Word numbers the figures for you. If you insert a new figure in the middle later, the numbers renumber themselves.

*Check: the caption text sits under the image in small italic text and starts with "Figure 1", "Figure 2", and so on.*

---

## End-of-semester checklist

If you followed the steps above every week, all of this is already done:

- [x] Header on every page
- [x] Footer with page numbers on every page
- [x] Table of contents (just hit Update Field one last time)
- [x] Image captions (Word numbered them)
- [x] Version history in the Document Control table
- [ ] Final read-through for typos
- [ ] Confirm the repo is still public

---

## If something breaks

**The table of contents shows old page numbers.**
Right-click it → Update Field → Update entire table.

**A new section is missing from the table of contents.**
The heading is not using a Heading style. Go to Step 2.

**The page numbers in the footer show the wrong total.**
Print Preview (Ctrl+P) forces Word to recalculate, then close it.

**I accidentally deleted a big chunk.**
GitHub has every past version. Open the repo → click the file → **History** → pick an older commit → download it.
