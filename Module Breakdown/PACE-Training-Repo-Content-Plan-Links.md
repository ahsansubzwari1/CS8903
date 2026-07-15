# PACE Training Repo — Content Build Plan (with Links)

**Repo structure:** one new GitHub repo, folders `101/` `201/` `301/` `401/`, each with a `README.md` sequencing that module's files in order, plus a top-level `/pdf-exports/` folder holding the Scribe PDF versions (unused for now, kept for reference).

**Classification legend**
- **Scribe** — screen-recorded click-through, exported as markdown with screenshots.
- **Hybrid** — Scribe recording of the terminal/CLI session *plus* a markdown code block with the exact copy-pasteable commands.
- **Markdown Explainer** — original prose, written by us, explaining what something is and when/why to use it.
- **Markdown Pointer** — a short paragraph + link out to someone else's existing resource.

---

## 101 — Access & Setup

| # | File | Type | Link(s) |
|---|------|------|---------|
| 1 | `101-01-How to Install and Configure GlobalProtect VPN.md` | Scribe — **Done** | Scribe capture: https://scribehow.com/o/RwVvEgxYTayBbEjBpzDTfg/viewer/101-How_to_Install_and_Configure_GlobalProtect_VPN__eb_p94lRTzeLuHtmrvnpqg <br> Referenced KBs: [KB0042139 — Configure the GT VPN](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042139) · [KB0026743 — Install GlobalProtect for macOS](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0026743) · [KB0026742 — Install GlobalProtect for Windows](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0026742) <br> Portal: vpn.gatech.edu |
| 2 | `101-02-Logging Into OnDemand and SSH.md` | Scribe — **not yet built** | Proposed source: [KB0042133 — OnDemand Guide & Other Clusters](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042133) *(currently also referenced in 201 — see note below)* |
| 3 | `101-03-Understanding the PACE Ecosystem.md` | Markdown Explainer | [PACE Homepage](https://pace.gatech.edu/) · [Get Started with PACE](https://pace.gatech.edu/participation/) |
| 4 | `101-04-Requesting ICE Access.md` | Markdown Pointer | [Request ICE Access (Form)](https://gatech.service-now.com/technology?id=sc_cat_item&sys_id=02ca19891b06309429eba8e2b24bcbe5) |
| 5 | `101-05-Orientation Resources.md` | Markdown Pointer | [User Orientation (KB0042355)](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042355) · [PACE Setup Video Walkthrough](https://www.youtube.com/watch?v=Ou9RwpOXx-w) · [PACE Orientation Workshop Videos](https://mediaspace.gatech.edu/channel/PACE/283315292) |
| — | `README.md` | — | Sequences 101-01 → 101-05 |

---

## 201 — Running Your First Job

| # | File | Type | Link(s) |
|---|------|------|---------|
| 1 | `201-01-The Four Numbers Before You Submit.md` | Markdown Explainer | No external link — original content |
| 2 | `201-02-Finding Your Sizing Recipe.md` | Markdown Pointer | [HAAG Compute & Storage Guide — Recipe Index](https://github.com/ahsansubzwari1/HAAG-Compute-Sizing-Guidelines/blob/main/README.md) |
| 3 | `201-03-Choosing Your GPU.md` | Markdown Pointer | [Part 3 — GPU Decision Tree](https://github.com/ahsansubzwari1/HAAG-Compute-Sizing-Guidelines/tree/main/03%20-%20Choosing%20Your%20ICE%20GPU) |
| 4 | `201-04-Using the VRAM Calculator.md` | Markdown Explainer | [VRAM Calculator (live tool)](https://ahsansubzwari1.github.io/HAAG-Compute-Sizing-Guidelines/tools/vram-calculator/index.html) |
| 5 | `201-05-Submitting Your First Job.md` | Hybrid | [Sample Slurm Script — KB0042096](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042096) |
| 6 | `201-06-Further Reading.md` | Markdown Explainer | [Intro-To-PACE-ICE (Guru Deshpande)](https://github.com/guru-desh/Intro-To-PACE-ICE) |
| — | `README.md` | — | Sequences 201-01 → 201-06 |

*Note: `KB0042133` (OnDemand Guide) currently appears as a candidate source for both 101-02 and 201. Recommend it anchors 101-02 (first login) and 201 simply assumes OnDemand/SSH access already works, to avoid duplicating the same KB across two modules.*

---

## 301 — Storage, Troubleshooting & Support

| # | File | Type | Link(s) |
|---|------|------|---------|
| 1 | `301-01-Storage on ICE.md` | Markdown Explainer | [Storage Guide (ICE) — KB0042094](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042094) |
| 2 | `301-02-Auditing Your Storage Usage.md` | Markdown Pointer | No public link — contact Justin Yiu directly |
| 3 | `301-03-Validating Your Job Before Submission.md` | Markdown Pointer | No public link — contact Zach Wallace directly |
| 4 | `301-04-Checking System Status.md` | Markdown Explainer | [PACE System Status](https://pace.gatech.edu/system-status/) |
| 5 | `301-05-Getting Help.md` | Markdown Explainer | [Consultation Sessions — KB0042280](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042280) · [PACE Policies — KB0042198](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042198) · `hpchelp@gatech.edu` |
| — | `README.md` | — | Sequences 301-01 → 301-05 |

---

## 401 — Specialized Workloads & Staying Current

| # | File | Type | Link(s) |
|---|------|------|---------|
| 1 | `401-01-Running LLMs with Ollama.md` | Hybrid *(pending confirmation)* | [PACE + HAAG: Ollama — KB0044774](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0044774) |
| 2 | `401-02-Staying Current.md` | Markdown Pointer | [PACE Trainings, Workshops & Events](https://pace.gatech.edu/pace-trainings/) |
| 3 | `401-03-Distributed Training.md` | *Placeholder* | TBD — Fall 2026 Build track, no link yet |
| 4 | `401-04-Bioinformatics.md` | *Placeholder* | TBD — Fall 2026 Build track, no link yet |
| — | `README.md` | — | Sequences 401-01 → 401-04 |

---

## Links still missing
- **101-02** has no confirmed source KB of its own yet — using `KB0042133` provisionally. Worth checking that KB actually covers first-login OnDemand/SSH steps before building the Scribe off it.
- **301-02 / 301-03** have no public URLs — these stay as direct-contact pointers to Justin and Zach until/unless their tools get their own repos or pages.
- **401-03 / 401-04** have no content yet — links get filled in once those recipes ship in the Fall Build track.
