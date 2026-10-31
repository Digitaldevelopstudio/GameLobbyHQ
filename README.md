# GameLobbyHQ — Frontend Preview

This is a responsive static frontend preview for GameLobbyHQ.

## Included
- Dark gaming-themed landing page
- English / Roman Urdu switcher
- GTA V / GTA VI selector
- Player finder UI with platform, region and community-rank filters (sample data)
- Featured player and sample rankings
- Sample lobby cards
- Create-lobby and account modal previews
- Responsive mobile layout

## Important
This is a frontend prototype only. Profiles, login, real chat, friend requests, realtime lobbies, verified game ranks, XP, moderation, and persistent data are NOT connected yet. Do not collect real user passwords with this static version.

## Deploy on GitHub Pages
1. Create a new repository named `gamelobbyhq`.
2. Upload `index.html` to the repository root using GitHub's web UI.
3. Go to Settings → Pages.
4. Under Build and deployment, select Deploy from a branch.
5. Choose `main` and `/ (root)`, then Save.
6. After publishing, connect your domain in Settings → Pages → Custom domain.

## Next development phase
Integrate Supabase Auth, database tables, Row Level Security, live lobby updates, player messaging, moderation/reporting, and real community rank calculations. GTA VI data and online features must only be added after verified official information is available.
