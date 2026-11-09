# Breast Cancer Wisconsin Classification

Source code for the Breast Cancer Wisconsin Classification project. This repository contains the Python application and model utilities, the original dataset and notebook, and the React frontend.

## Project structure

- `frontend/` — React + TypeScript web interface.
- `app.py` — Python application entry point.
- `predictive_system.py` — prediction utility.
- `report_generator.py` — report generation utility.
- `trained_model.sav` — serialized model required by the prediction workflow.
- `breast-cancer-wisconsin.csv` — dataset file.
- `Breast-Cancer Classification.ipynb` — analysis notebook.

## Frontend setup

Install Node.js, then run:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL shown by Vite (usually `http://localhost:5173`).

## Python setup

From the repository root:

```bash
pip install -r requirements.txt
```

Run the Python entry point appropriate to your local environment. Check the source configuration before deployment and update any machine-specific paths.

## Important notice

This project is for educational and research purposes only. It is not a medical device and must not be used as a substitute for professional medical diagnosis or treatment.
