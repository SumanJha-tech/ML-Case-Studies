# ⚡ Energy Vision Using Weather

Predicting and exploring energy patterns from multi-city weather data, served through a Flask web app.

## Problem

Energy demand moves with the weather. This project combines weather data from several cities with energy data, stores it in SQL, and exposes the results in a web interface.

## What is in this folder

| Path | Purpose |
|---|---|
| `City dataset/` | Per-city source data |
| `Combined12.csv` | Merged dataset used for modelling |
| `Database.sql` | SQL schema for storing the data |
| `app.py` | Flask application |
| `templates/`, `static/` | Web UI (HTML, CSS, JS) |

## Approach

1. **Collect and merge** the per-city files into `Combined12.csv`.
2. **Clean** missing values and align dates. [FILL: details]
3. **Model**: [FILL: algorithm(s), features, target, train/test split]
4. **Evaluate**: [FILL: metrics such as R², MAE, RMSE]
5. **Serve** predictions through `app.py`.

## Results

| Model | R² | MAE |
|---|---|---|
| [FILL] | [FILL] | [FILL] |

[FILL: 2–3 sentences on the key finding, e.g. which weather variable mattered most.]

## Screenshots

[FILL: add 1–2 screenshots of the web app, e.g. `![App](static/screenshot.png)`]

## Run locally

```bash
pip install -r requirements.txt
# optional: load the schema into your database
psql -f Database.sql
python app.py
```

Open http://127.0.0.1:5000

## Tech stack

`Python` `Pandas` `scikit-learn` `Flask` `SQL` `HTML/CSS`

## Author

[Suman Jha](https://github.com/SumanJha-tech) · ✉️ sumanjha0906@gmail.com · [LinkedIn](https://linkedin.com/in/sumanjha-tech)
