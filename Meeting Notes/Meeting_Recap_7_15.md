# Weekly Recap — PACE HPC Training Series

**Project:** HAAG-HPC-TRAINING repo
**Author:** Ahsan Subzwari

## Summary
Repo scaffolding now exists for all four modules. Module 3 (Storage, Troubleshooting & Support) is fully built and shipped this week — all five files plus README, sourced from Justin Yiu's and Zach Wallace's actual HAAG tools rather than placeholder links. Module 1 has two of five files genuinely live. Module 2 has the folder structure in place but no written content yet.

## Module 1 — Access & Setup (Bilal & Pranav)
- **101 — GlobalProtect VPN** — live, Scribe capture
- **102 — Logging Into OnDemand and SSH** — live, Scribe capture. This closes the access gap flagged a couple weeks ago (VPN connects, but nothing walked through the first OnDemand/SSH login)
- 103, 104, 105 — folders scaffolded, content not yet written

## Module 2 — Running Your First Job (Ahsan)
- Folder structure and all six file placeholders (201–206) are scaffolded in the repo
- No content written yet — flagging this since the live repo doesn't yet show it as done; let me know if there's a draft elsewhere I should pull in before this shows up in any report

## Module 3 — Storage, Troubleshooting & Support (Ahsan) — complete
All five files plus README shipped this week:
- **301** — Storage on ICE
- **302** — Auditing Your Storage Usage (Justin Yiu's real storage audit tool/script)
- **303** — Validating Your Job Before Submission (Zach Wallace's real validator)
- **304** — Checking System Status
- **305** — Getting Help

Pulled directly from the actual HAAG admin repo rather than the placeholder "contact them directly" notes from before. Two things surfaced worth following up on:
- Zach's own doc has a broken `git clone` command — corrected version is in 303, worth a heads-up to him
- PACE's current support page lists `pace-support@oit.gatech.edu`, not `hpchelp@gatech.edu` — worth confirming which is current before this goes out broadly

## Module 4 — Specialized Workloads & Staying Current
- Folder structure and all four file placeholders (401–404) scaffolded
- Content not yet started (401 and 402 are buildable now; 403 and 404 wait on Fall Build track recipes)

## Housekeeping
- The top-level repo README is stale — still describes the old flat `101/ 201/ 301/ 401/` naming plan rather than the `100 - / 200 - / 300 - / 400 -` structure actually in use. Worth a quick update so it matches reality.

## Next steps
- Fill in Module 1's remaining three files (103–105)
- Start Module 2 content
- Bring the storage sanitation proposal to this week's meeting — 301 and 302 feed it directly
