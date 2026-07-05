# Publishing this site (the RED step — yours)

The repo is staged and committed. To go live:

1. Create the GitHub repo (e.g. `marathon-brane`) on your account.
2. `cd ~/marathon-brane-site`
3. `git remote add origin git@github.com:bobdiscuits/marathon-brane.git`
4. `git push -u origin main`
5. GitHub Pages: follow Quartz's hosting doc (`docs/hosting.md`) — add its GitHub Actions deploy workflow, then Settings → Pages → Source: GitHub Actions.
6. If your final URL differs, update `baseUrl` in `quartz.config.ts` and push again.

**Brane-only vs. both:** the repo currently ships BOTH halves (Brane + Mirror). To publish analysis-only, add "Mirror" to `ignorePatterns` in `quartz.config.ts` — the hubs' footnotes still link out to karnemir. `CONTENT-LICENSE.md` covers the both-halves case.

**Refresh after vault edits:** re-run the rsync in `README-DEMO.md`, plus `_tools/artifact_index.py` + `_tools/export_console.py` in the vault, then copy `_index/console_snapshot.html` → `content/console.html`, commit, push.

> Note: Quartz emits `content/console.html` at the clean URL `/console`. After deploy, verify it renders on GitHub Pages; if it downloads instead, move the file to `quartz/static/` and link `/static/console.html`.
