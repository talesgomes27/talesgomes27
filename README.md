# Tales Gomes
### Data Scientist & Data Analyst

Data professional focused on applied statistics, reproducible pipelines, and interactive analytical tools. 
I work with exploratory data analysis, statistical modeling, and data application deployment to translate raw numbers into validated operational decisions.

[LinkedIn](https://linkedin.com/in/talesgomes27) · [Online Resume](https://talesgomes27.github.io/curriculo/) · [Technical Blog](https://blog-talesgomes.netlify.app/) · [Email](mailto:talesgomes27@gmail.com)

---

## Featured Projects

### 📈 [YouTube Virality: Dual Modeling, Simpson's Paradox & Audience Deconfounding](https://github.com/talesgomes27/youtube_viral_video_prediction)
End-to-end analytical and machine learning pipeline on 12,000 YouTube videos across 15 editorial categories, isolating channel scale inertia from actionable creator levers.

* **Methodology & Modeling**: Deconfounded video duration via Simpson's Paradox resolution, showing the raw negative correlation ($r = -0.2015$) disappears when normalized by channel scale ($r = -0.0077$). Runtime data validation contracts (`DC-01` to `DC-07`) strictly blocking target and proxy leakage. Dual modeling with stratified 5-fold CV: viral classification ($P_{80}$, views $\ge 734\text{k}$) achieving $\text{PR-AUC} = 0.7407$ and $\text{ROC-AUC} = 0.9086$, plus log-reach regression ($\text{RMSLE} = 0.9457$, $R^2_{\ln} = 0.6716$). Global and local explainability via TreeSHAP and gain-based feature importance.
* **Tech Stack**: `Python`, `uv`, `LightGBM`, `scikit-learn`, `SHAP`, `Quarto`, `pytest`, `Ruff`
* **Artifacts**: [Published Report (GitHub Pages)](https://talesgomes27.github.io/youtube_viral_video_prediction/) · [Source Code](https://github.com/talesgomes27/youtube_viral_video_prediction)

---

### 💳 [Bank Fraud Mitigation: Three-Stage Hurdle Model & Financial Calibration](https://github.com/talesgomes27/credit_card_fraud_detection)
Modular pipeline processing 100,000 credit card transactions to balance direct loss reduction against legitimate customer friction costs.

* **Methodology & Modeling**: Three-stage Hurdle architecture replacing mono-stage classifiers: binary detection (`is_fraud`) with financial threshold tuning ($C(t) = \sum \text{FN} \cdot \text{Loss} + \$3.50 \cdot \text{FP}$), multiclass fraud typing across 4 attack categories via Macro F1-score, and conditional loss quantification via RMSE/MAE. Behavioral feature engineering covering velocity bursts and transaction ticket deviations, coupled with global and local SHAP explainability.
* **Tech Stack**: `Python`, `uv`, `LightGBM`, `scikit-learn`, `SHAP`, `Quarto`, `pytest`, `Ruff`
* **Artifacts**: [Published Report (GitHub Pages)](https://talesgomes27.github.io/credit_card_fraud_detection/) · [Source Code](https://github.com/talesgomes27/credit_card_fraud_detection)

---

### 🚕 [NYC Taxi Trip Duration: Geospatial Engineering & Gradient Boosting](https://github.com/talesgomes27/improve_traffic)
Predictive pipeline estimating urban transit durations across New York City by coupling historical taxi dispatch records with daily meteorological observations.

* **Methodology & Modeling**: Geodesic and Manhattan grid feature engineering (Haversine, orthogonal distances, bearing angles, airport access flags). Analysis of severe weather deceleration effects. Outlier treatment and log-transformed target optimization ($\text{RMSLE}$). Temporal validation split benchmarking tree ensembles, where a tuned LightGBM model achieved an $\text{RMSLE}$ of 0.3397 ($\text{MAE}$ of 3.25 min, $R^2 = 0.7934$). Complete with a modular Python pipeline, Makefile automation, and automated unit tests.
* **Tech Stack**: `Python`, `LightGBM`, `XGBoost`, `scikit-learn`, `pandas`, `Quarto`, `Makefile`
* **Artifacts**: [Published Report (GitHub Pages)](https://talesgomes27.github.io/improve_traffic/) · [Source Code](https://github.com/talesgomes27/improve_traffic)

---

### 🚲 [Cyclistic Bike-Share: Statistical Inference & Customer Conversion](https://github.com/talesgomes27/DAC8-Case-Study-1)
Case study based on Chicago's Divvy bike-sharing data, structuring data-driven marketing strategies to convert casual riders into annual members.

* **Methodology & Statistics**: Data hygiene pipeline filtering invalid trips and out-of-bounds coordinates. Vectorized Haversine formula for geodesic travel distances. Non-parametric hypothesis testing (Wilcoxon rank-sum, Chi-square with Cramér's V). Binomial logistic regression estimating Odds Ratios for member behavior, alongside customer persona segmentation and an A/B testing framework.
* **Tech Stack**: `R`, `Quarto`, `tidyverse`, `ggplot2`, `scales`
* **Artifacts**: [Published Report (GitHub Pages)](https://talesgomes27.github.io/DAC8-Case-Study-1/) · [Source Code](https://github.com/talesgomes27/DAC8-Case-Study-1)

---

### ☄️ [NASA Fireballs: Bolide Impacts & Atmospheric Energy Analysis](https://github.com/talesgomes27/nasa_fireball)
Interactive application analyzing bolide and meteor impact events recorded by the NASA/JPL CNEOS sensor network.

* **Architecture & Physics**: Kinetic energy calculation via Brown et al. (Nature, 2002) empirical scaling law. Interactive 3D globe and planar geospatial projections via Plotly. HTTP ingestion pipeline with automatic fallback to local serialized snapshots. Compiled client-side to WebAssembly via Shinylive/webR for zero-cost static hosting.
* **Tech Stack**: `R Shiny`, `bslib (Bootstrap 5)`, `Plotly`, `reactable`, `Shinylive (WebAssembly)`
* **Artifacts**: [Live Dashboard (shinyapps.io)](https://talesgomes27.shinyapps.io/nasa_fireball/) · [Serverless App (GitHub Pages)](https://talesgomes27.github.io/nasa_fireball/) · [Source Code](https://github.com/talesgomes27/nasa_fireball)

---

### ⚙️ [Autonomous Agent Meta-Skills: Multi-Gate Pipeline Architecture](https://github.com/talesgomes27/antigravity-meta-skills)
Governance framework and operational protocols orchestrating AI coding agents across 5-gate deterministic software engineering and data science workflows.

* **Architecture & Governance**: Lifecycle pipelines spanning pre-code planning, test-driven execution, technical writing, release ops, and non-destructive legacy audit. Polymorphic dispatch tailored to archetypes: Data Science/Quarto (CRISP-ML(Q) and data storytelling), Web/APIs (DDD and Clean Architecture), and CLI tools.
* **Tech Stack**: `Markdown`, `Bash`, `Python / uv`, `Quarto`, `Git`
* **Artifacts**: [Source Code & Architecture](https://github.com/talesgomes27/antigravity-meta-skills)

---

## Technical Toolkit

* **Statistical Analysis & Machine Learning**: Python (pandas, scikit-learn, LightGBM, XGBoost, SHAP), R (tidyverse, ggplot2), SQL (PostgreSQL, SQLite), Quarto.
* **Interactive Tools & Interfaces**: R Shiny, bslib (Bootstrap 5), Plotly, reactable, Shinylive (WebAssembly).
* **Environment & Tooling**: `uv`, Git, GitHub Actions, Linux / Bash, Makefile, Docker foundations.

## Engineering Standards

* **Reproducibility**: Parameterized pipelines, deterministic random seeds, and frozen Quarto execution caches (`freeze: auto`).
* **Data Contracts & Leakage Prevention**: Strict runtime contract assertion (`DC` rules) blocking target and proxy leakage across inference splits.
* **Empirical Validation**: Cost-sensitive financial thresholds, effect sizes, non-parametric checks, and confidence intervals prioritized over raw point estimates.
