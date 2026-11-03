# QA screenshots: profile README, where the work is (adamthede/adamthede#2)

Captured 2026-11-02 with Playwright (Chromium headless shell 1248) and compressed with pngquant.

## After state, at PR head ac1dade

Each shot is the live github.com/adamthede profile, in the light theme, with the README article's contents replaced by GitHub's own markdown-API render (gfm mode, adamthede/adamthede context) of the README that merging this PR into main produces. That merge is computed with `git merge-tree --write-tree origin/main ac1dade` against main at 81ad993, so the activity entry is main's current one. Nothing else on the page was changed, so the sidebar, bio and pinned repos are live.

- after-profile-desktop-1280.png: 1280 px viewport, from the top of the page to the end of the README. The seven-entry list sits between the opening paragraph and "Ask me about", and the streak card is gone.
- after-profile-phone-390.png: 390 px viewport at 2x, from the top of the page to the end of the README. The seven entries wrap without horizontal scroll.

These replace two earlier sets. The first, at head 30be0f0 with eight entries, stays reachable at commit a457a0137459a165c1ca4b8cacf57cf54ae5234c. The second, at head a57968f with "The Reading Life", stays reachable at commit 2efc8a4e9299064d754105642d3c9d4675bbbcd7. Renaming it "A Reading Life" shortened that entry from three lines to two at 390 px, so the shots were taken again.

Before shots of the same README, minus this section and with the streak card, are in ../pr-1/.

This branch exists only to host the images at a pinned commit. It is not meant to merge.
