# BIOSTAT 707 — Checkpoint 1 (PhysioNet/CinC Challenge 2012, set-a)

1. Download dataset-a from https://physionet.org/content/challenge-2012/1.0.0/ and unzip so the repo root contains `data/set-a/<RecordID>.txt` (4000 files) and `data/Outcomes-a.txt`. `data/` is gitignored.
2. From the repo root run `pixi run --locked checkpoint1`. This installs the pinned environment from `pixi.lock` and runs `checkpoint1.ipynb` top to bottom.
3. Files written to `output/`:
   - `set-a_long.csv` — one row per measurement, as loaded
   - `set-a_wide.csv` — one row per record: descriptors, per-variable summaries, outcomes
   - `checkpoint1.html` — the rendered notebook with all tables and figures
4. Only `output/checkpoint1.html` is committed; everything else in `output/` is regenerated on each run.

*** AI Use Statement is provided at the end of notebook. The majority of code was generated with AI help in step by step rather than hands-off agentic way.


*** Edit (10/08/2026): Although I already provided two AI use statements in the notebook. I would like to provide further transparency. The context provided is the requirements of submission, upload, writing the read.me, and background on the data. Requirements such as long/wide tables and other questions for the project. For some reason, it struggled in providing interesting questions about how to best clean the data and informative missingness (so it took a few iterations to get a good code block). Initially after asking it to generate tables, I noticed the extremes for some variables. I then asked it to go through every variable to suggest which ones are truly impossible. I had the final decision in determining what to keep and what to drop. Then, I requested that it create the corresponding rule set code block.
Please let me know if you have further questions. I am happy to answer and be transparent about the process.
