# Junior Stream

A curriculum board for a junior pickleball coaching program, in one self-contained page (`index.html`).

- **Curriculum:** skills (dinks, resets, third shot drops, serve and return, volleys), each with levels. Every level has a pro clip to watch, a drill and a "move up when" standard. YouTube clips play inline.
- **Players:** mark the last level each player has passed; the board flags the level the middle of the group should work on.
- **Sessions:** plan a session from levels, with a warm-up and a finish game.
- **Present:** a full-screen court-side view of the session, with a drill timer.

Live site: https://jfbest-tech.github.io/junior-stream/

## Where edits are saved

Edits made on the page save in **that viewer's browser only** (`localStorage`). They are not sent anywhere, are not shared with anyone else, and do not change this repo. Clearing browser data or switching devices or browsers starts again from the version in `index.html`.

Once a browser has saved edits, it keeps showing its own copy, so changes pushed to `index.html` later will not appear in that browser until its site data for this page is cleared.

## Privacy

This repo and the site are public. **Never commit player names** or anything else that identifies a child. The `players` list in `index.html` stays empty (`"players":[]`); add players on the page itself, where they stay in your own browser.

Practice footage is ignored by `.gitignore` (`*.mp4`, `*.mov`) so it cannot be committed by accident. Link clips from YouTube instead.
