# Harrow Reach: the site

The public site for Harrow Reach, a space trading and combat game in Rust.
Served by GitHub Pages from the root of `main`.

- `index.html`: the front page and screenshots.
- `manual.html`: the player's manual.
- `assets.html`: the asset brief, **generated**. Its source is
  `docs/assets.html` in the game repo; edit that and run
  `scripts/publish-site-assets.sh --push` there. Hand edits here are
  overwritten.
- `screenshots/`: captured from the current build, game window only.

Plain HTML and one stylesheet, no build step.
