# Helper script

Optional script referenced in the tutorial.

## Python

| Script | Purpose | Section |
|---|---|---|
| `bootstrap_ci.py` | 95% bootstrap confidence intervals from a sentence-level COMET spreadsheet | Part 4.3 |

Requirements:

```bash
pip install pandas numpy openpyxl
```

Usage:

```bash
python python/bootstrap_ci.py 
```

This presumes that `sentence_level_comet.xlsx` is in the same working directory.

> **Tip.** Modern LLMs will adapt or extend these scripts on demand.
> Try a prompt like "modify `bootstrap_ci.py` to also compute Pearson
> correlation between each system column and a column called
> `human_grade`."
