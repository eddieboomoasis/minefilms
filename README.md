# Eddie DaRoza — Mining Films

Portfolio site. Documentary cinematography and post for mining companies.
Static HTML + four self-hosted 34-second excerpt clips. No build step, no dependencies.

- `index.html` — the whole site
- `clips/` — four excerpt clips (mp4, h264, faststart) + poster frames

Clips are 34-second excerpts of client-commissioned films, self-hosted so nothing depends on a
third-party player. `preload="none"` means no video downloads until a visitor presses play.

**Source films** live in Google Drive; masters are not in this repo.

## To take the site down
Settings → Pages → set Source to "None", or delete the repo. Both are immediate.
