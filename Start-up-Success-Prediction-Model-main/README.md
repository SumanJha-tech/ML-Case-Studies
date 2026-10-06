# 🚀 Start-up Success Prediction Model

A classification model that estimates whether a start-up is likely to succeed, based on company features.

## Problem

Investors and founders want an early read on which start-ups are likely to succeed. This project builds a model from historical company data and measures how well it predicts the outcome.

## Dataset

| Item | Detail |
|---|---|
| Source | [FILL: e.g. Kaggle / Crunchbase dataset name] |
| Rows | [FILL] |
| Target | [FILL: e.g. status = acquired / operating vs closed] |
| Key features | [FILL: e.g. funding total, funding rounds, location, industry, age] |

## Approach

1. **Clean**: handle missing values, remove duplicates, fix dates. [FILL]
2. **Engineer features**: [FILL: e.g. funding per round, company age]
3. **Split** into train and test sets. [FILL: ratio, stratified?]
4. **Train and compare** models: [FILL: e.g. Logistic Regression, Random Forest, XGBoost]
5. **Evaluate** with metrics that fit the class balance.

## Results

| Model | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| [FILL] | [FILL] | [FILL] | [FILL] | [FILL] |

**Top predictors:** [FILL: 3 most important features]

[FILL: 2–3 sentences on what the model tells you in business terms.]

## Run locally

```bash
pip install -r requirements.txt
jupyter notebook   # or: python [FILL: script].py
```

## Limitations

- Historical data reflects past market conditions.
- Success is influenced by factors not in the dataset (team, timing, luck).
- Use it to rank and prioritise, not to make a final investment call.

## Tech stack

`Python` `Pandas` `scikit-learn` `Matplotlib`

## Author

[Suman Jha](https://github.com/SumanJha-tech) · ✉️ sumanjha0906@gmail.com · [LinkedIn](https://linkedin.com/in/sumanjha-tech)
