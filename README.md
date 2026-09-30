# CISC7021NLP_A2

CISC7021 Applied NLP — Assignment 2.

Zero-shot prompting and fine-tuning of `rzzhan/tiny-llama-stories-42m` (41.7M params) on
Rotten Tomatoes (binary) and SST-5 (5-class), with a 4-page ACL-format report.

## Contents

- `notebook/CISC7021_Assignment2_TinyLlama2_Sentiment.ipynb` — full pipeline: zero-shot prompting,
  fine-tuning, optional experiments (heads / linear probing), error analysis.
- `results/` — the 10 required result files (`rto|sst5` x `val|test` x `prompting|finetuned`,
  plus `task1-scores.txt`, `task3-scores.txt`).
- `report/` — `main.tex`, `main.pdf` (4 pages), ACL style files, bibliography, Overleaf zip.
- `artifacts/` — metrics records, error-case dumps, negation-share statistics.
- `figures/` — confusion matrices, metric comparisons, per-class F1, training curves.

Note: model checkpoints are not tracked in this repository.
