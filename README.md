# Hi, I'm Arseniy 👋

I'm a third-year AI Engineering student at ITMO University in St. Petersburg, focused on classical ML, tabular data, feature engineering and time-series forecasting.

I work on reproducible ML pipelines, from data preparation and validation to model tracking and serving. I'm looking for paid remote junior ML / Data Science opportunities.

## Selected projects

### [FX Predictor AI - USD/EUR Forecasting Service](https://github.com/Vladimir-119/fx-predictor-ai)
Joint project with Vladimir Volkov: a reproducible forecasting service built with FastAPI, PostgreSQL, MLflow, RustFS, RabbitMQ/FastStream and Docker Compose.

- Compared six model configurations using three expanding-window validation folds and a 63-observation chronological holdout.
- Regularized CatBoost reduced MAE versus the last-rate baseline by **0.84% on CV and 2.01% on holdout** (0.00193443 vs 0.00197407 EUR per USD). These are preliminary historical results; the holdout had been inspected during research and a new period is needed for confirmation.
- Shared lag and rolling feature logic between training and inference; tracked data snapshots, experiments and registered models in MLflow, with explicit candidate-to-champion promotion.
- Added asynchronous inference, task status retrieval, bounded queues, retries and idempotent PostgreSQL result storage; integrated stale-data checks and GitHub Actions CI.

### [Wind Power Generation Forecasting](https://github.com/SenX1/Train_Twins-wind-prediction)
Built an ensemble of 11 CatBoost models with Ridge stacking for a 90.09 MW wind farm. Features captured air density, wind shear, lagged observations and rolling statistics; validation used TimeSeriesSplit with a temporal gap.

- Q1 2026 leaderboard: 7.987% normalized MAE.
- Separate forecasting period: 2nd on the private leaderboard, approximately 2.7 MW MAE.

### National Technological Olympiad 2024 - Geospatial Data Analysis
1st place, team CGM. Worked with Sentinel-2 imagery, QGIS, coordinate system reconstruction, FABDEM terrain features and NDVI time series for crop analysis and yield forecasting.

## Tools

- **ML:** Python, CatBoost, scikit-learn, Ridge, Optuna, SHAP, model validation, probability calibration, feature engineering.
- **Data:** pandas, NumPy, Polars, SQL, PostgreSQL.
- **ML engineering:** MLflow, FastAPI, Pydantic, Docker, Docker Compose, Git, RustFS (S3-compatible storage), RabbitMQ, FastStream, GitHub Actions, pytest, Ruff, uv.
- **Geospatial:** GeoPandas, QGIS, Rasterio, CRS.


## Contact

[Telegram](https://t.me/quitepeaky) · [LinkedIn](https://www.linkedin.com/in/senx) · [Email](mailto:arseniyjvagin@gmail.com)
