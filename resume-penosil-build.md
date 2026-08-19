# Resume: Penosil reseller page build

Paste this whole thing into a new chat on your work account to pick up where you left off.

---

I'm continuing a front-end build I started in a previous chat (on my personal account, which hit its limit — this is my separate work account now). Here's the full context:

**Project:** Pixel-accurate HTML/CSS prototype of a Penosil reseller-facing web page, built section by section from a Figma design.

**References:**
- Figma file: `tA99sMZww2FqSLEehQPDO3` ("TEST")
- Live reference site: https://penosil.com/et/ (different page, used for style/behavior reference — buttons, hover states, spacing)

**Working directory:** `/home/claude/nav-preview/`, output zipped as `nav-preview.zip`

**Workflow we were using (please keep following this):**
1. I share/select the next Figma frame (via node link or by having it selected in Figma)
2. You pull design context for that specific section node (not the parent frame)
3. I export and upload the actual assets (icons, photos, backgrounds) from Figma myself — you can't fetch Figma asset URLs directly from the sandbox, so don't attempt to approximate/hand-draw placeholders; wait for me to upload real assets
4. You build the section in HTML/CSS (vanilla JS where needed, e.g. accordions)
5. I check it against Figma and against penosil.com/et/, flag anything off
6. We fix, then move to the next section

**Sections completed so far, in order:**
1. Navbar
2. Hero (with background wrapper, watermark)
3. Highlight cards (4 cards overlapping the hero image — this one was tricky)
4. Product cards with hover states (hover changes text to red on "Know Our Product"; cards matched to equal width)
5. Product spotlight section with certification badges
6. YouTube video section (fixed: video needed to fill screen, no green edges)
7. Partner registration form (left info column with benefits list + checkmark icon, right side contact form — fixed swapped placeholder labels in form fields)
8. FAQ accordion — 4 items, one expanded by default with a highlighted answer card and inline link; built as a single plus-icon SVG rotated 45° via CSS for the expand/collapse state (this was the last thing in progress)

**Where I left off:** I'd just said "do the next section for now and we'll do another pass on the whole page with these minor fixes" — so there are known minor fixes pending a final pass, and the FAQ accordion section was just being finished. I need to select the next frame after FAQ in Figma to continue, or do the fix pass first.

**Things to remember:**
- `get_design_context` should target the specific section node ID, not a parent frame
- `get_metadata` with no `nodeId` reads whatever I currently have selected in Figma
- I download/export Figma assets myself and upload them — don't try to fetch them directly

---

Let me know if you want the fix-pass first or to keep moving section by section.
