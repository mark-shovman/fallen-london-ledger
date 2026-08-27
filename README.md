# Fallen London Character Ledger

A character-creation tool for *Fallen London: the Roleplaying Game*, built from the
corebook preview (chapters 2, 3, 4 and 6). One self-contained HTML file — no build
step, no dependencies, nothing to install.

## What's here

| File | What it is |
|---|---|
| `index.html` | The ledger itself. Open it in any browser, or serve it from GitHub Pages. |
| `kit-catalogue.md` | The Chapter 6 equipment and resource catalogue in editable form. The ledger has a **Load catalogue…** button on the Kit step that reads this file, so you can correct an entry and see it immediately. |

## Publishing it on GitHub Pages

1. Create a repository on GitHub and upload both files to the root (drag and drop
   works: **Add file → Upload files**).
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`, then **Save**.
3. Wait a minute or two. The site appears at
   `https://<your-username>.github.io/<repository-name>/`.

GitHub Pages serves a public site. On the free plan, Pages for a private repository
is not available — see *A note on the rulebook text* below before you publish.

## Using it

Pick one option in each of the six identities and the sheet on the right fills
itself in: menace tracks, skill ranks with what each rank buys on a roll, obsession
strengths and charges, Areas of Expertise, kit, traits and abilities. The checks
panel tells you what is still unspent or over a limit.

* **Save file** writes a `.json` of the character; **Load…** reads one back.
* **Export PDF** prints a two-page character sheet.
* Characters live in those `.json` files, not in the page, so they survive updates.

## A note on the rulebook text

The ledger embeds a lot of text from the corebook preview — every option's
mechanical effect, and the full catalogue entries. That is fine for your own table;
putting it on a public website republishes a large part of someone else's
unreleased book. If you want a public link, consider trimming the entries to names
and page references, or ask Failbetter first.
