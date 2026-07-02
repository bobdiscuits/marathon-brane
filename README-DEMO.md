# Marathon Brane — local demo site

Quartz v4.5.2 wrapping `/Users/bobdiscuits/V2.0 Marathon Brane` (Brane + Mirror, machinery excluded).

**Relaunch:** `cd ~/marathon-brane-site && npx quartz build --serve` → http://localhost:8080

**Refresh content after vault edits:**
    rsync -a --exclude ".git" --exclude ".obsidian" --exclude ".DS_Store" \
      --exclude "_tools" --exclude "_index" --exclude "_bases" \
      "/Users/bobdiscuits/V2.0 Marathon Brane/" ~/marathon-brane-site/content/
    npx quartz build --serve

**Demo route:** home → a Thread (The Marathon Incident) → Durandal → his "Mirror pages" block (the twin's own 1:1 ground truth, local) → the graph view (855 hub→Mirror edges, 1994 → Season 2) → search anything.

**To publish** (the RED step, Bob's call): decide Brane-only vs Brane+Mirror (ignorePatterns in quartz.config.ts), set real baseUrl, `npx quartz sync` to a GitHub repo + Pages. Note: Quartz v5 (main) renders Obsidian .base files — revisit when its plugin installer stabilizes so the _bases views can ship too.

*Built 2026-07-02 by Tine. Backend gates at build time: verify_fm 79/79 green · 0 invalid citations · 855 mirror edges, 0 unmapped.*
