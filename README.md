# OpenSheets

OpenSheets is an **experimental, single-file web app** (everything lives in `index.html`) that’s intended as a lightweight “spreadsheet-like” playground you can run locally or host as a static site. :contentReference[oaicite:0]{index=0}

> Repo note: the repository currently has **no GitHub description/topics set**, so this README is written to be accurate to the current repo layout (static HTML-only project) and to give you a solid baseline you can extend as features evolve. :contentReference[oaicite:1]{index=1}

---

## What this repo is

- **Static site / no build step**: HTML-only project (GitHub reports **HTML 100%**). :contentReference[oaicite:2]{index=2}  
- **Single entry point**: `index.html` is the app. :contentReference[oaicite:3]{index=3}  
- **License added**: Apache-2.0. :contentReference[oaicite:4]{index=4}  

---

## Quick start (local)

### Option A — simplest
1. Download/clone the repo
2. Open `index.html` in your browser

### Option B — recommended (local web server)
Some browsers apply stricter rules when opening files directly (`file://`). Running a tiny local server avoids that:

```bash
# from the repo folder
python -m http.server 8000
