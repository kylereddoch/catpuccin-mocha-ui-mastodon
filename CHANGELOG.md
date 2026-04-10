### 2.0.0 2026-04-07

- Rebuilt the project around a pinned Bird UI 3.0.0 snapshot for Mastodon v4.5.0-era styling.
- Added `catppuccin-bird-ui.user.css` as the new recommended Stylus install with configurable Catppuccin flavors, accents, layout widths, surface styles, and composer side.
- Added a static `layout-single-column.css` export so the regular Mastodon view can share the same Catppuccin theme baseline.
- Replaced the previously duplicated and injected advanced-web stylesheet with generated clean outputs.
- Added `scripts/build-theme.ps1` so future Bird UI syncs and theme rebuilds are repeatable.

### 1.0.2 2025-09-25

- Updated for Mastodon v.4.4.0, v.4.4.1, v.4.4.2, v4.5.0-alpha.1.
- Updated to match [BirdUI's 2.3.3 release](https://github.com/ronilaukkarinen/mastodon-bird-ui/releases/tag/2.3.3).
- Fixed a few margin issues around the search box in the left compose area I have had on my to-do list for awhile

### 1.0.1 2025-01-23

- Removed heard animation from BirdUI
- Restored original Mastodon heart animation
- Fixed hashtag bar hover color
- Fixed follow button background color in user account search results

### 1.0.0: 2025-01-10

-  First stable release
