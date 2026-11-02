# QA screenshots: profile README, one identity (adamthede/adamthede#1)

Captured 2026-11-02 with Playwright and compressed with pngquant.

## Current after state, at PR head b3c7f8d

Each shot is the live github.com/adamthede profile with the README article's contents replaced by GitHub's own markdown-API render of the README that merging this PR into main produces. That merge is computed with `git merge-tree origin/main b3c7f8d`, so the activity entry is main's current one. Nothing else on the page was changed, so the sidebar, bio and pinned repos are live. This is the method the reviewer used for the review evidence.

- after-profile-desktop-1280.png: 1280 px viewport, top of page. The bio carries the identity sentence and the README opens on the apps. The sentence appears once on the page.
- after-profile-phone-390.png: 390 px wide, from the top of the page to the end of the README. The bio sits above the README, and the sentence appears once.

## Before, live profile

- before-desktop.png: 1280 px viewport, first load, an element crop of the README. The stats card shows as a broken image.
- before-phone.png: 390 px viewport, an element crop of the README, after the stats card's cache warmed.

## Superseded

- after-desktop.png and after-phone.png show the README at head cdcd525 in GitHub's file view. That version opened with the identity sentence, which the bio already carries, so it is superseded by the profile shots above.

This branch exists only to host the images at a pinned commit. It is not meant to merge.
