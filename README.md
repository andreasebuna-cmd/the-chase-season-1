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
- `timeline.json` — original timeline source; the game loads this file at runtime.
- `GAMEPLAY.md` — supplied game mechanics specification.

## Current scope

The site implements the menu, chapter list, dialogue/cutscene progression, context-sensitive choices, local save/resume, pause, fullscreen and the three final outcomes defined in the timeline. It uses only the supplied timeline and mechanics as narrative sources. The mechanics document itself notes that some parameters (including exact combat damage, attack cadence and death/retry rules) remain unspecified; those values are not invented here.
