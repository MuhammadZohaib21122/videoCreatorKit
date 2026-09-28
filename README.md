# CreatorKit — YouTube creator toolkit

Open `index.html` in a modern desktop or mobile browser. No installation, local server, API key, or account is required.

## Included tools
Title generator, description generator, hashtag generator, thumbnail analyzer, thumbnail downloader, video idea generator, Shorts idea generator, script generator, tag generator, channel name generator, engagement calculator, video duration calculator, and revenue estimator.

All writing/idea generators use **local, editable template logic**, not an AI model. Results are starting points to personalize and fact-check. The thumbnail analyzer calculates simple image properties and offers heuristic guidance; it cannot predict click-through rate, recognize objects/text, or replace real audience testing. Revenue calculations are hypothetical estimates based on the RPM *you* enter, not actual earnings. Engagement is calculated as `(likes + comments + shares) / views × 100` using the values supplied.

The thumbnail downloader loads standard public YouTube thumbnail URLs when available. It does not fetch or download videos. Saving external images can be restricted by a browser's cross-origin settings; use the open-image fallback if this happens. Only use thumbnails you have the rights to use.

Favorites, recent tools, and theme preferences use your own browser's localStorage. A future channel dashboard is shown as a roadmap teaser, not a connected feature. This independent website is not affiliated with YouTube.

## Files
- `index.html` — structure and interactive tool dialog
- `styles.css` — responsive YouTube-inspired visual design
- `app.js` — all tools, rendering, validation, interactions
- `favicon.svg` — project icon

## Updated card interaction (v1.1)
- Click or tap anywhere on a tool card to open it, including the title, description, icon and “Open tool” area.
- Each card has an accessible full-card button (keyboard: Tab then Enter/Space).
- The heart button still adds/removes favorites without opening the tool.
- Cards have hover, click, focus and icon/arrow animations; reduced-motion preferences are respected.
