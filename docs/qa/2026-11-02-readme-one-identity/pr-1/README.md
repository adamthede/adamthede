# QA screenshots: profile README, one identity (adamthede/adamthede#1)

Captured 2026-11-02 with Playwright, element screenshots of the rendered README, compressed with pngquant.

- before-desktop.png: live profile at github.com/adamthede, 1280 px viewport, first load. The stats card shows as a broken image.
- before-phone.png: live profile, 390 px viewport, after the stats card's cache warmed.
- after-desktop.png: the PR branch README in GitHub's file view, 1280 px viewport.
- after-phone.png: the same, 390 px viewport.

GitHub renders the profile only from main, so the after shots use the file view. The README render is the same markdown renderer, without the profile sidebar around it.

This branch exists only to host the images at a pinned commit. It is not meant to merge.
