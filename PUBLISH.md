# SHIP IT — your three commands (the RED step)

Everything is staged: clean history, deploy workflow, license, README, console at a Pages-safe path.

1. Create the repo at https://github.com/new — name it **marathon-brane**, Public, NO readme/license/gitignore (we have them).
2. In Terminal:
   ```
   cd ~/marathon-brane-site
   git remote add origin git@github.com:bobdiscuits/marathon-brane.git
   git push -u origin main
   ```
   (HTTPS instead of SSH if you prefer: `https://github.com/bobdiscuits/marathon-brane.git`)
3. On GitHub: repo **Settings → Pages → Source: GitHub Actions**. The included workflow (`.github/workflows/deploy.yml`) builds and deploys on every push (~2 min).

Live at: **https://bobdiscuits.github.io/marathon-brane/** (matches the baseUrl already set in quartz.config.ts — if you name the repo differently, change baseUrl to match and push again).

Tell Claude the moment it's up → live smoke-test: sample pages across all tiers, the console download, search, graph, and a link-sweep.

**Notes:** the one-file console ships at `/static/console.html` (Pages-safe, linked from the front door). Brane+Mirror+Leela all ship, per your call. To go Brane-only later: add "Mirror" to ignorePatterns in quartz.config.ts, push.

**Refresh after vault edits:** run the rsync in README-DEMO.md, plus in the vault: `_tools/artifact_index.py` → `_tools/export_console.py --theme dark` → copy `_index/console_snapshot.html` to `quartz/static/console.html`; commit; push. Actions redeploys automatically.
