# THE CHASE — Season 1

Static, browser-based narrative game. The interface is designed for Cloudflare Pages and does not require a build step or external packages.

## Deploy to Cloudflare Pages

1. Open Cloudflare Dashboard → **Workers & Pages** → **Create** → **Pages**.
2. Connect the GitHub repository `andreasebuna-cmd/the-chase-season-1`.
3. Choose **Production branch**: the repository's default branch.
4. Set **Framework preset** to **None**.
5. Leave **Build command** empty.
6. Set **Build output directory** to `.` (the repository root).
7. Deploy.

Every commit to the connected production branch will trigger a new deployment.

## Files

- `index.html` — full-screen cinematic UI and interactive game loop.
- `timeline.json` — original timeline source; arc descriptions, causes, conditions, results and outcomes are loaded at runtime.
- `story-dialogue.json` — authored dialogue for all 50 timeline events, including the three endings.
- `GAMEPLAY.md` — supplied game mechanics specification.
- `GAMEPLAY_SYSTEMS.md` — implementation status, provisional combat values and remaining work.
- `ASSET_GUIDE.md` — cinematic image names and art direction; the scene slots are wired into the interface.

## Current scope

The current prototype includes authored dialogue, object inspection, a persistent clue dossier, contextual text-answer puzzles, combat actions, a shared 10,000-HP boss pool across three phases, save/resume across gameplay phases, consequence tracking and conditional ending requirements. Combat values remain provisional; richer puzzle interfaces and several boss mechanics are outstanding. Add the cinematic images to assets/scenes using the exact filenames in ASSET_GUIDE.md.
