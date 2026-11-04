# Society Wives — Story Library

A mobile-friendly reader built from the original **Prologue** and **Society Wives — Episode 3 Master Pack** Google Doc tabs. Both source texts live in one editable GitHub file.

## The ONE file you edit

**[content/STORY.md](content/STORY.md)** — this is the source of truth for the reader.

1. Open **content/STORY.md** on GitHub.
2. Click **Edit this file** (pencil icon).
3. Modify the Prologue or Episode 3 text, or scroll to the end to add a new episode.
4. Click **Commit changes** to save.
5. Refresh the website after GitHub Pages finishes publishing. The reader loads the latest content file on every visit.

### Adding Episode 4 (no programming required)

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
- Full Episode 3 Master Pack, including headings, timeline, sections and Parts A–F per character
- Automatic navigation for newly added chapters
- In-chapter table of contents and links
- Search the open chapter (press /)
- Dark/light themes and adjustable font size
- Responsive mobile/desktop reading UI
- No build step, database, or content-management service required

## Provenance

Google Doc: **Yeh revised Ep1 pack hai — pehle wale clone se alag**.

- Prologue tab: 0 — Prologue (Dhika-style), ID t.hybe3sy4qfjc.
- Episode 3 tab: Society Wives — Episode 3 Master Pack, ID t.fyz7ytl1vbhn.

Wording was retained, with Markdown formatting for headings. Other tabs were not imported.

**Privacy:** This GitHub repository is public, so the uploaded story text is publicly accessible. If the text should not be public, use a private repository and hosting arrangement instead.

## Structure

    index.html         Website UI
    content/STORY.md   Single file to edit
    .nojekyll          Pages compatibility
    README.md          Instructions
