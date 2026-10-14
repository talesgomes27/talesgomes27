# Tales Gomes
### Data Scientist & Data Analyst

Data professional focused on applied statistics, reproducible pipelines, and interactive analytical tools. 
I work with exploratory data analysis, statistical modeling, and data application deployment to translate raw numbers into validated operational decisions.

[LinkedIn](https://linkedin.com/in/talesgomes27) · [Online Resume](https://talesgomes27.github.io/curriculo/) · [Technical Blog](https://blog-talesgomes.netlify.app/) · [Email](mailto:talesgomes27@gmail.com)

---

## Featured Projects

### 🚲 [Cyclistic Bike-Share: Statistical Inference & Customer Conversion](https://github.com/talesgomes27/DAC8-Case-Study-1)
Case study based on Chicago's Divvy bike-sharing data, structuring data-driven marketing strategies to convert casual riders into annual members.

* **Methodology & Statistics**: Data hygiene pipeline filtering invalid trips and out-of-bounds coordinates. Vectorized Haversine formula for geodesic travel distances. Non-parametric hypothesis testing (Wilcoxon rank-sum, Chi-square with Cramér's V). Binomial logistic regression estimating Odds Ratios for member behavior, alongside customer persona segmentation and an A/B testing framework.
* **Tech Stack**: `R`, `Quarto`, `tidyverse`, `ggplot2`, `scales`
* **Artifacts**: [Published Report (GitHub Pages)](https://talesgomes27.github.io/DAC8-Case-Study-1/) · [Source Code](https://github.com/talesgomes27/DAC8-Case-Study-1)

---

### 🚕 [NYC Taxi Trip Duration: Geospatial Engineering & Gradient Boosting](https://github.com/talesgomes27/improve_traffic)
Predictive pipeline estimating urban transit durations across New York City by coupling historical taxi dispatch records with daily meteorological observations.

* **Methodology & Modeling**: Geodesic and Manhattan grid feature engineering (Haversine, orthogonal distances, bearing angles, airport access flags). Analysis of severe weather deceleration effects. Outlier treatment and log-transformed target optimization ($\text{RMSLE}$). Temporal validation split benchmarking tree ensembles, where a tuned LightGBM model achieved an $\text{RMSLE}$ of 0.3397 ($\text{MAE}$ of 3.25 min, $R^2 = 0.7934$). Complete with a modular Python pipeline, Makefile automation, and automated unit tests.
* **Tech Stack**: `Python`, `LightGBM`, `XGBoost`, `scikit-learn`, `pandas`, `Quarto`, `Makefile`
* **Artifacts**: [Published Report (GitHub Pages)](https://talesgomes27.github.io/improve_traffic/) · [Source Code](https://github.com/talesgomes27/improve_traffic)

---

### ☄️ [NASA Fireballs: Bolide Impacts & Atmospheric Energy Analysis](https://github.com/talesgomes27/nasa_fireball)
Interactive application analyzing bolide and meteor impact events recorded by the NASA/JPL CNEOS sensor network.

* **Architecture & Physics**: Kinetic energy calculation via Brown et al. (Nature, 2002) empirical scaling law. Interactive 3D globe and planar geospatial projections via Plotly. HTTP ingestion pipeline with automatic fallback to local serialized snapshots. Compiled client-side to WebAssembly via Shinylive/webR for zero-cost static hosting.
* **Tech Stack**: `R Shiny`, `bslib (Bootstrap 5)`, `Plotly`, `reactable`, `Shinylive (WebAssembly)`
* **Artifacts**: [Live Dashboard (shinyapps.io)](https://talesgomes27.shinyapps.io/nasa_fireball/) · [Serverless App (GitHub Pages)](https://talesgomes27.github.io/nasa_fireball/) · [Source Code](https://github.com/talesgomes27/nasa_fireball)

---

## Technical Toolkit

* **Statistical Analysis & Machine Learning**: Python (pandas, scikit-learn, LightGBM), R (tidyverse, ggplot2), SQL (PostgreSQL, SQLite), Quarto.
* **Interactive Tools & Interfaces**: R Shiny, bslib (Bootstrap 5), Plotly, reactable, Shinylive (WebAssembly).
* **Environment & Tooling**: Git, GitHub Actions, Linux / Bash, Makefile, Docker foundations.

## Engineering Standards

* **Reproducibility**: Parameterized pipelines, structured seed setting, and documented data dictionaries.
* **Defensive Ingestion**: Timeouts, payload schema verification, and offline serialized fallbacks for external APIs.
* **Empirical Validation**: Effect sizes, non-parametric checks, and confidence intervals prioritized over raw point estimates.
