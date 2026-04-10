### 2.0.0 2026-04-10

- Rebuilt the project around a generated theme pipeline based on a pinned Bird UI `3.0.0` snapshot aligned with Mastodon `4.5.0`.
- Renamed the project to `Catppuccin Complete UI for Mastodon`.
- Added `catppuccin-complete-ui.user.css` as the main Stylus/UserCSS install, with `catppuccin-bird-ui.user.css` kept as a compatibility alias for older installs.
- Added configurable Catppuccin flavor switching for `Mocha`, `Macchiato`, `Frappe`, and `Latte`.
- Added configurable accent color selection across the Catppuccin palette.
- Added configurable advanced-web options for composer side, composer width, timeline column width, surface treatment, and optional active-header glow.
- Added support for both the advanced web interface and the regular single-column Mastodon view from the same theme system.
- Added `layout-single-column.css` as a generated default export for the regular Mastodon layout.
- Rebuilt `layout-multiple-columns.css` as a clean generated advanced-web export instead of the older duplicated hand-edited CSS.
- Added organized fixed exports under `themes/` for every Catppuccin flavor and accent combination in both layouts.
- Added `scripts/build-theme.ps1` to make Bird UI syncs and theme rebuilds reproducible.
- Added support in the build script for pinned builds, custom Bird UI refs, and rebuilding against the latest stable Bird UI tag.
- Expanded accent color coverage across more of the UI, including headers, hashtag links, compose actions, drawer controls, and related interface elements.
- Improved readability and contrast handling across light and dark Catppuccin variants, including fixes for Latte and Frappe problem areas.
- Fixed advanced-web layout details including the larger left-side composer behavior, compose search icon placement, hover/follow button readability, and newer Mastodon notification/conversation text selectors.
- Removed the broken navigation width control from the configurable userstyle.
- Refreshed the README, install instructions, branding, and generated CSS headers to match the new project structure and naming.

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
