# BIOSTAT 707 — Checkpoint 1 (PhysioNet/CinC Challenge 2012, set-a)

1. Download dataset-a from https://physionet.org/content/challenge-2012/1.0.0/ and unzip so the repo root contains `data/set-a/<RecordID>.txt` (4000 files) and `data/Outcomes-a.txt`. `data/` is gitignored.
2. From the repo root run `pixi run --locked checkpoint1`. This installs the pinned environment from `pixi.lock` and runs `checkpoint1.ipynb` top to bottom.
3. Files written to `output/`:
   - `set-a_long.csv` — one row per measurement, as loaded
   - `set-a_wide.csv` — one row per record: descriptors, per-variable summaries, outcomes
   - `checkpoint1.html` — the rendered notebook with all tables and figures
4. Only `output/checkpoint1.html` is committed; everything else in `output/` is regenerated on each run.