# Society Wives — Story Library

A mobile-friendly reader built from the original **Prologue**, **Episode 1 Master Pack**, **Episode 2 Master Pack**, and **Episode 3 Master Pack** Google Doc tabs. All four source texts live in one editable GitHub file.

## Writing Studio — prompts and draft workflow

Open **[Writing Studio](studio.html)** (or `https://developer-fandom-rush.github.io/Society_Story/studio.html`) to prepare Episode 1 with Grok. The studio reads the existing Episode 1 Master Pack from `content/STORY.md` instead of maintaining a second copy of the prompts. It includes the Master System, the existing Prologue as a reference, the optional Shared Prologue rewrite prompt, and all 25 character Parts (A–E for each wife) with one-click copy.

**First Grok paste:** Section 1 — MASTER SYSTEM, in a fresh chat. The Prologue already exists in the linked source tab. Use it as context or optionally rewrite it; then write **Ankita Part A**, followed by Ankita B–E and the other four heroines in order.

Paste each Grok result into its matching draft field. Checkmarks and drafts are saved **only in that browser**; use **Download this draft** or **Download all drafts** before changing devices. These drafts do not update GitHub automatically. To publish, add reviewed prose to `content/STORY.md` and commit.

The current [Story Library reader](index.html) remains separate from the Writing Studio. No existing chapter text is overwritten by opening or using the studio.

## The ONE file you edit

**[content/STORY.md](content/STORY.md)** — this is the source of truth for the reader.

1. Open **content/STORY.md** on GitHub.
2. Click **Edit this file** (pencil icon).
3. Modify the Prologue or any existing episode text, or scroll to the end to add another chapter.
4. Click **Commit changes** to save.
5. Refresh the website after GitHub Pages finishes publishing. The reader loads the latest content file on every visit.

### Adding Episode 4 or a later chapter (no programming required)

At the end of content/STORY.md, append:

    # Society Wives — Episode 04

    ## Episode 04 — Introduction

    Paste your new content here.

    ## Ankita

    Paste Ankita's episode content here.

    ## Shivani

    Paste Shivani's episode content here.

    ## Shreya

    Paste Shreya's episode content here.

    ## Taniya

    Paste Taniya's episode content here.

    ## Meenakshi

    Paste Meenakshi's episode content here.

Every first-level Markdown heading beginning with a hash and space (# ) becomes a NEW chapter automatically in the site's navigation. Use two hashes (## ) for section headings and three hashes (### ) for subsections. You never have to edit the HTML or a manifest.

Keep the first chapter named **Prologue** if you want the Prologue's automatic five-character introduction cards. They are drawn from paragraphs that begin with Ankita, Shivani, Shreya, Taniya, and "Aur Meenakshi". Change those paragraphs to change the cards.

## Publishing once with GitHub Pages

This repository was initially empty, so GitHub Pages might not yet be enabled.

1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**.
4. Choose **Branch: main**, folder **/ (root)**, then **Save**.
5. Wait for GitHub Pages to publish. The expected site URL is:

   https://developer-fandom-rush.github.io/Society_Story/

Publishing may take a couple of minutes. The same URL updates when content/STORY.md changes on the main branch. No new URL is needed.

## Features

- Full Prologue with five expandable character introduction cards
- Complete Episode 1, Episode 2, and Episode 3 Master Packs, including headings, timeline, sections and per-character Parts
- Automatic navigation for newly added chapters
- In-chapter table of contents and links
- Search the open chapter (press /)
- Dark/light themes and adjustable font size
- Responsive mobile/desktop reading UI
- No build step, database, or content-management service required

## Provenance

Google Doc: **Yeh revised Ep1 pack hai — pehle wale clone se alag**.

- Prologue tab: 0 — Prologue (Dhika-style), ID t.hybe3sy4qfjc.
- Episode 1 tab: Society Wives — Episode 1 Master Pack, ID t.0.
- Episode 2 tab: Society Wives — Episode 2 Master Pack, ID t.7lxosvxlb7bm.
- Episode 3 tab: Society Wives — Episode 3 Master Pack, ID t.fyz7ytl1vbhn.

Wording was retained, with Markdown formatting for headings. Other tabs were not imported.

**Privacy:** This GitHub repository is public, so the uploaded story text is publicly accessible. If the text should not be public, use a private repository and hosting arrangement instead.

## Structure

    index.html         Website UI
    content/STORY.md   Single file to edit
    .nojekyll          Pages compatibility
    README.md          Instructions
