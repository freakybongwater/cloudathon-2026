# Cloud-a-thon @ UH 2026 — AI Challenge (Team 8)

Team 8: Zach, Yousef, Ben, Nevin

Our submission for the Cloud-a-thon @ UH 2026 AI Challenge: a supervised-learning
walkthrough on the **Bank Marketing** dataset, predicting which clients subscribe
to a term deposit and turning that into a call list the business can act on.

## What's here

- `Team8_Zach_Yousef_Ben_Nevin.html` — the full executed notebook exported to HTML
  (open it in a browser; all code, plots and outputs are embedded).

## Notebook outline

1. Setup and imports
2. Data quality — types, ranges, missing data, duplicates, holding out validation/test rows before EDA
3. Visual EDA — target counts, histograms, box plots, count plots, correlation heatmap, pairplot
4. Preprocessing
5. Train / validation / test split
6. Models — baseline decision tree
7. Additional models — pre-pruned tree, logistic regression, random forest, gradient boosting
8. Model comparison and threshold selection
9. Final model selection
10. Business recommendation — calls, savings and the ranked client list

## Viewing it

Clone the repo and open the HTML file in any browser:

```bash
git clone <repo-url>
cd cloudathon-2026
start Team8_Zach_Yousef_Ben_Nevin.html   # Windows
```
