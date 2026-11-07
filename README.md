# Society Wives — Story Reader & Writing Prompts

[Open the website](https://developer-fandom-rush.github.io/Society_Story/) · [GitHub repository](https://github.com/developer-fandom-rush/Society_Story)

## The two separate sections

The website has two clearly labeled reading modes:

| Actual Story | Writing Prompts |
| --- | --- |
| **Prologue** and the existing **Episode 01 — Story (Grok + GPT Inserts)** | **Episode 01–04, 05A/B/C, and 06/06A/06B/06C Master Packs** |
| Source: [content/STORY.md](content/STORY.md) | Source: [content/PROMPTS.md](content/PROMPTS.md) |
| Real reading prose, edited/published manually | Plans, source-locked writing instructions, episode parts, continuity |
| New finalized Episode 02, 03, etc. go here | Future prompt packs go here; NOT the finished story |

**Important:** The existing Episode 01 reading chapter is the version already in the repository. Its heading indicates **Grok + GPT Inserts**. If you have a different approved/final Episode 01, replace that chapter's text in **STORY.md**; it is not automatically synced from Google Docs or writing drafts.

The **Episode 04 Master Pack is not the final Episode 04 story**. It is available in **Writing Prompts**, and its 25 part-writing steps are also accessible in [Episode 04 Writing Studio](episode4.html).

## Manually edit the existing Episode 01 Story

1. Go to **[content/STORY.md on GitHub](https://github.com/developer-fandom-rush/Society_Story/blob/main/content/STORY.md)** and sign in to your GitHub account.
2. Click the **pencil (Edit this file)**. If the pencil is hidden, use the file's **…** menu.
3. Find the existing heading:

       # Society Wives — Episode 1 — Story (Grok + GPT Inserts)

4. Edit or replace the prose **under that heading** with your approved Episode 01 reading content. Keep the Prologue unchanged unless you expressly want to revise it. Do **not** add a duplicate Episode 01 chapter.
5. Click **Commit changes**, add a short commit message, and commit to `main` (or open and merge a pull request if GitHub requires it).
6. Check [Actions](https://github.com/developer-fandom-rush/Society_Story/actions). Once the GitHub Pages build finishes, open the [Actual Story view](https://developer-fandom-rush.github.io/Society_Story/?view=story) and refresh.

## Manually add finalized Episode 02 (and later episodes)

1. Open [content/STORY.md](https://github.com/developer-fandom-rush/Society_Story/blob/main/content/STORY.md).
2. Click **Edit this file**.
3. Go to the bottom, after the existing Episode 01 story. Add a new top-level heading `#` followed by the **finalized reading prose**, for example:

```md
# Society Wives — Episode 02 — Story

## Ankita
Paste Ankita's finalized scene prose here.

## Shivani
Paste Shivani's finalized scene prose here.

## Shreya
Paste Shreya's finalized scene prose here.

## Taniya
Paste Taniya's finalized scene prose here.

## Meenakshi
Paste Meenakshi's finalized scene prose here.
```

4. Click **Commit changes** and wait for GitHub Pages to deploy. Refresh **Actual Story**. No HTML editing is needed.
5. For Episode 03 and later, repeat using a new `# Society Wives — Episode 03 — Story`, etc. Keep episodes ordered.

**Heading rules:** `# ` creates a new episode/chapter; `## ` creates a section or character scene; `### ` creates a smaller subpart. Never paste Master Pack prompts into the Story file.

## Manually update or add writing prompts

1. Open [content/PROMPTS.md](https://github.com/developer-fandom-rush/Society_Story/blob/main/content/PROMPTS.md).
2. Click the pencil icon.
3. Find the applicable `# Society Wives — Episode 04 Master Pack ...` heading to revise that prompt, or append `# Society Wives — Episode 05 Master Pack` to introduce a new prompt chapter.
4. **Commit changes** and refresh [Writing Prompts](https://developer-fandom-rush.github.io/Society_Story/?view=prompts).

Both sections use GitHub files, not Google Docs live synchronization. Any edits you make in Google Docs must be deliberately transferred into the correct file before they appear on the site.

## Writing Studios

- [Episode 01 Writing Studio](studio.html): extracts the Episode 01 Master System, optional Shared Prologue rewrite prompt and 25 heroine part prompts from **PROMPTS.md**. It reads the existing Prologue from **STORY.md**, as a separate reference.
- [Episode 04 Writing Studio](episode4.html): extracts the Episode 04 Master System and 25 heroine part prompts from **PROMPTS.md**.
- Completed checkboxes and draft text are stored **locally in that browser only**; they are **not** published. Use each studio's download buttons to export drafts, review and finalize the prose, then paste it manually into **STORY.md**.

## Reader features

- Separate **Actual Story** and **Writing Prompts** selectors, with chapter-specific navigation.
- Prologue character-introduction cards, in-chapter section contents and chapter search (/).
- Dark/light modes, adjustable font size, responsive desktop/mobile layout.
- The reader immediately renders a built-in chapter snapshot and then refreshes from the two GitHub Markdown files; an unavailable Markdown request should not blank the reader. GitHub Pages must deploy each change for the public URL to update.
- Old links to a prompt chapter using `?chapter=...` still open the matching prompt section.

## GitHub Pages publishing

GitHub Pages is deployed from the repository. To check it: **Settings → Pages**, and **Actions** for the latest build. The public address stays:

https://developer-fandom-rush.github.io/Society_Story/

A committed change may take a minute or more to publish. Refresh the page after the build finishes. You do not need a new public link for every episode.

## Source provenance

The original Episode 01–04 planning prompts were copied from the multi-tab Google Doc. Episode 06 was added from the approved [Episode 06 Master Pack (A/B/C) + Ep3 Corrections](https://docs.google.com/document/d/1M3asHCA7UmHF2KiARwlaPfBsNkHdRDc6idPHyzYYOio/edit), split into four UI chapters (overview, 06A, 06B, 06C). These are **one-time copies**, not automatically synced from Google Docs.

- Episode 01 Master Pack tab: `t.0`
- Episode 02 Master Pack tab: `t.7lxosvxlb7bm`
- Episode 03 Master Pack tab: `t.fyz7ytl1vbhn`
- Episode 04 Master Pack tab: `t.xux6qy3fxewz`
- Prologue: `t.hybe3sy4qfjc`

**Privacy:** This repository is public; anything you commit to it can be read by other people. Do not add personal data or text you do not intend to publish.

## Repository structure

```
index.html          Story/Prompts reader UI + GitHub editing guide
content/
  STORY.md          Prologue + published episode prose
  PROMPTS.md        Episode 01–06 planning Master Packs (05A/B/C and 06A/B/C)
studio.html         Episode 01 Writing Studio
episode4.html       Episode 04 Writing Studio
.nojekyll           GitHub Pages compatibility
README.md           These instructions
```



## Dhika — original chapters and corrected episode numbering

The third homepage tile opens [Dhika Original Story Reader](dhika.html?tab=original&chapter=0), a dedicated full-text reader, separate from Society Wives prose and Writing Prompts.

- **Source of truth:** [Dhika Forum Episode Index — DOM Extraction](https://docs.google.com/document/d/1DRuJKSOep0Eo93ZLCKGK4PxErv6kY2uo4uNZFrxerxo/edit?tab=t.3i71lj73ib3d). Its **Prologue + 40 story tabs** (41 total) have been imported in their exact Google Doc tab order.
- **Correct author episode numbering:** The final source tab explicitly reads **Episode 41 — Birthday Party: A Total Strip-down**. Since some source episodes span multiple tabs, tab index is not an episode number. The **next proposed episode is EP42**.
- **Future Mexico proposed arc:** EP42–48, with India video calls; **India return EP49–51**. These are proposals, NOT already published source episodes. Prior planning EP70–79 labels have been superseded.
- **Older analysis labels EP55, EP68, EP69:** These came from a separate reconstructed ledger and are not author episode numbers. They remain marked as legacy evidence and must be mapped carefully.
- **Original full text:** Nine JSON groups, content/dhika-source/part-01.json through part-09.json, loaded lazily by the reader. Original wording and line breaks are preserved. Metadata is in content/DHIKA_ORIGINAL_INDEX.json.
- **Future plot files:** [content/DHIKA_MEXICO.md](content/DHIKA_MEXICO.md) and [content/DHIKA_MEXICO.json](content/DHIKA_MEXICO.json). The latter drives the episode/action interface.
- **Public access:** Original Google Doc text has been copied into this public GitHub repository at the user's request. Public viewers can read it; the Google Doc itself was not modified.

### Dhika reader URLs

[Original Prologue](dhika.html?tab=original&chapter=0) · [Last source chapter (Author EP41)](dhika.html?tab=original&chapter=40) · [Proposed EP42](dhika.html?tab=episodes&ep=42) · [India Return](dhika.html?tab=return) · [Relationship Ledger](dhika.html?tab=relationships).

### Maintenance

To update the original source, re-export Google Docs and update the nine JSON groups and manifest together; this is not a live automatic sync. Editing the Markdown future plan alone does not automatically update its JSON. Preserve original source versus planning separation.

## Dhika — Sexcapades with the Twins Part 4 (proposed)

[Open five-part Twins reader](twins.html?ep=52) · [Structured scene actions](content/DHIKA_TWINS_PART4.json) · [Readable planning pack](content/DHIKA_TWINS_PART4.md)

- **Corrected future episode numbers:** original author source ends at **EP41**; Mexico remains proposed **EP42–48**, India Return **EP49–51**, and the new five-part Twins Part 4 is **EP52–56** (4A–4E). Old draft EP79–83 numbers are retired for this future arc.
- **Reader:** standalone `twins.html`, linked from the main `dhika.html` navigation. Five parts, 41 proposed scenes, per-scene non-graphic action names, search, character filters, per-part highest milestone, plot mechanism, boundary notes and next hooks.
- **Canon protection:** original Google Docs source tabs and story chapter JSON files were not changed. Secondary legacy analysis numbering (1–69) may differ from author numbering and is clearly marked. Adult intimacy references are non-graphic planning tags, frequently off-page, never a claim that future scenes already occurred.
- **Public publishing:** the GitHub Pages deployment serves the same URLs after the corresponding commit is built; edits to the JSON/Markdown update the reader without changing the link.
