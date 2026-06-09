# Heart Stroke Prediction

This repository contains a Streamlit app to predict heart disease risk using a trained KNN model.

How to run locally:

1. Create a Python environment (conda or venv).

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2. Run the app:

```bash
streamlit run app.py
```

Files of interest:
- `app.py` — Streamlit app
- `KNN_heart.pkl`, `scaler.pkl`, `columns.pkl` — model artifacts (already in repo)

Deployment:
- Create a GitHub repo and push your code. Then deploy on Streamlit Cloud or another hosting provider.

License: Add a license if you want this project public.
