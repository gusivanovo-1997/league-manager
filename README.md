# League Manager

A futsal league run from one page: fixtures and the draw, a live match screen
with the clock and the goal log, the table, squads, discipline, attendance,
the Golden Boot, finals, and a season bulletin.

**Open it here:** https://gusivanovo-1997.github.io/league-manager/

## How it works

It is a single HTML file with nothing behind it — no server, no account, no
database. A league lives in the browser you opened it in, so the page is a
tool rather than a service: whoever you send the link to gets an empty copy to
start their own, and nothing you do on your tablet reaches theirs unless you
set up sharing between them from the Settings tab.

Because it is one file it also works with no internet at all. Save the page and
it runs from a court with no signal.

## Keeping it on a tablet

Open the link, then **Add to Home Screen** (iPad: Share → Add to Home Screen;
Android: ⋮ → Add to Home screen). It opens like an app and keeps its league.

Two warnings worth knowing:

- The league is held in that browser's own storage. Clearing site data, or
  "clear history" with site data ticked, erases it. Take a backup from
  **Settings → Data** before a season matters.
- Private/incognito windows forget everything when they close.

## Updating it

This repository holds the published copy. The working copy lives in the
project repo; `scripts/publish-futsal.mjs` there copies the current build over
`index.html`, commits it and pushes, and GitHub Pages picks it up within a
minute or so.

AED Project Services
