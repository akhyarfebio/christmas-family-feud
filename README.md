# Christmas Family Feud 🎄

A standalone, host-operated Christmas Family Feud-style game for TV or projector. Contains 50 original Christmas survey-style rounds, two teams, revealable answers, automatic round-bank math, 3-strike animations, sound effects, custom team names, keyboard shortcuts, and local progress saving.

**Play locally:** Start any static web server in this folder, for example `python3 -m http.server 8000`, and open `http://localhost:8000`. No accounts, API keys, or external services are needed for the game. Online font files load when available; system fonts are used offline.

**Deploy to Vercel:** Import this folder's GitHub repository in Vercel, select Framework Preset `Other`, leave Build Command empty, Output Directory `.` (root), and deploy.

**Host shortcuts:** `1`–`8` reveal answers, `X` strike, `T` switch team, `A` award points, `N` next round, `F` fullscreen. Choose the correct answer manually; scores aren't based on live surveys. Points are fictional party-game survey scores.

**Note:** Changing to another round resets its reveals and strikes. Only the current round's state is saved, alongside cumulative scores. Award a bank only once per round to avoid duplicate scoring.
