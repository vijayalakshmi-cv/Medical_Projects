# Medical Projects (Notebooks)

This folder groups Jupyter notebooks related to medical AI / deep learning projects.

## Structure
- `notebooks/medical_imaging/` — MRI / X-ray / CT related CNN notebooks
- `notebooks/medical_signals/` — ECG / time-series (e.g., LSTM) notebooks
- `notebooks/other_ml/` — Supporting ML notebooks (ANN, data processing, visualization, API)

## Notes
- Some notebooks may contain environment-specific paths. Replace them with relative paths before running.
- Recommended: export key pipelines into scripts (`train.py`, `evaluate.py`) as the next step.

## How to run
```bash
pip install -r requirements.txt
jupyter lab
```
