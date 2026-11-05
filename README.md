# Society Wives — Story Reader & Writing Prompts

[Open the website](https://developer-fandom-rush.github.io/Society_Story/) · [GitHub repository](https://github.com/developer-fandom-rush/Society_Story)

## The two separate sections

The website has two clearly labeled reading modes:

| Actual Story | Writing Prompts |
| --- | --- |
| **Prologue** and the existing **Episode 01 — Story (Grok + GPT Inserts)** | **Episode 01–04 Master Packs** |
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

The planning prompts were originally copied from the multi-tab Google Doc (Master Pack tabs Episode 01–04). They are a **one-time copy**, not automatically updated when the Doc changes.

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
  PROMPTS.md        Episode 01–04 planning Master Packs
studio.html         Episode 01 Writing Studio
episode4.html       Episode 04 Writing Studio
.nojekyll           GitHub Pages compatibility
README.md           These instructions
```
