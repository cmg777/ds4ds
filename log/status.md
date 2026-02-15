# Project Status Log

## 2026-02-15: Repository restructure and website creation

### Changes made

- **README.md** updated to match website content at carlos-mendez.org/projects/ds4ds/
  - Title changed to "Computational Data Science Notebooks and Apps for Development Studies"
  - "Basic statistics" and "Basic econometrics" merged into "Basic statistics and econometrics"
  - Added new entries: statistics fundamentals, regressions, synthetic control explorer, ML Mincer equation, SHAP app, Google Earth Engine
  - Removed: OLS regressions and stargazer tables (replaced by new regressions notebook)

- **13 Colab notebooks downloaded** into the repo via gdown
  - gapminder_example.ipynb
  - real_differences_and_relationships.ipynb
  - statistics_differences_relationships_predictions.ipynb
  - descriptive_statistics_and_multi_boundary_mapping.ipynb
  - regressions_to_explore_relationships.ipynb
  - introduction_to_growth_equations.ipynb
  - solow_growth_model_python.ipynb
  - solow_growth_model_R.ipynb
  - convergence_clubs_labor_productivity.ipynb
  - esda_municipal_development_bolivia.ipynb
  - introduction_to_DAGs_R.ipynb
  - heterogeneous_treatment_effects_DID_R.ipynb
  - introductory_ml_mincer_equation.ipynb

- **OLS_using_stargazer_in_R.ipynb** deleted (replaced by regressions_to_explore_relationships.ipynb)

- **index.html** created as a single-page website
  - Modeled after quarcs-lab/metricsai design (Tailwind CSS, dark mode, glass-panel nav)
  - Green/teal color scheme
  - Sections: Hero, About, Notebooks (8 topic groups), Author, Citation, Resources, Footer
  - Responsive with mobile menu

### Current notebook inventory

| Section | Count | Status |
| --- | --- | --- |
| Basic Statistics and Econometrics | 5 notebooks | Complete |
| Economic Growth and Development | 4 notebooks | Complete |
| Exploratory Data Analysis | 1 notebook | Complete |
| Causal Inference | 2 notebooks + 1 app | Complete |
| Machine Learning | 1 notebook + 1 app | Complete |
| Spatial Econometrics | 0 | TBA |
| Bayesian Econometrics | 0 | TBA |
| Feature Engineering and Geocomputation | 1 GEE link | Partial (1 TBA) |

### Non-downloadable resources (external links only)

- Synthetic control explorer (GitHub Pages HTML app)
- SHAP plots interactive app (AI Studio)
- Google Earth Engine script
