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

## 2026-02-15: Notebook rename — language prefix convention

### Changes made

- **All 13 notebooks renamed** with programming language as first word
  - Python notebooks (9): prefixed with `python_`
  - R notebooks (4): prefixed with `r_`
  - Redundant language suffixes removed (e.g. `_python`, `_R`)

### Rename mapping

| Old name | New name |
| --- | --- |
| gapminder_example.ipynb | python_gapminder_example.ipynb |
| real_differences_and_relationships.ipynb | python_real_differences_and_relationships.ipynb |
| statistics_differences_relationships_predictions.ipynb | python_statistics_differences_relationships_predictions.ipynb |
| descriptive_statistics_and_multi_boundary_mapping.ipynb | python_descriptive_statistics_and_multi_boundary_mapping.ipynb |
| regressions_to_explore_relationships.ipynb | python_regressions_to_explore_relationships.ipynb |
| introduction_to_growth_equations.ipynb | python_introduction_to_growth_equations.ipynb |
| solow_growth_model_python.ipynb | python_solow_growth_model.ipynb |
| esda_municipal_development_bolivia.ipynb | python_esda_municipal_development_bolivia.ipynb |
| introductory_ml_mincer_equation.ipynb | python_introductory_ml_mincer_equation.ipynb |
| solow_growth_model_R.ipynb | r_solow_growth_model.ipynb |
| convergence_clubs_labor_productivity.ipynb | r_convergence_clubs_labor_productivity.ipynb |
| introduction_to_DAGs_R.ipynb | r_introduction_to_DAGs.ipynb |
| heterogeneous_treatment_effects_DID_R.ipynb | r_heterogeneous_treatment_effects_DID.ipynb |

- **index.html** updated: all 13 Colab links point to new filenames
- **README.md** updated: all 13 Colab links point to new filenames

## 2026-02-15: Julia gapminder notebook

- **julia_gapminder_example.ipynb** created — Julia version of the Gapminder intro notebook
  - Simplified from the Python version, focused on essential data science workflow
  - Uses CSV, DataFrames, Plots, GLM, StatsBase packages
  - Covers: import, summarize, visualize (scatter plots with log scale, multi-year panels), transform (log), model (OLS regression by continent)
  - Executed locally with Julia 1.12.4 kernel via `nbconvert` — all 20 code cells verified
- **index.html** updated: added Julia notebook card in Basic Statistics section (count 5→6, total 16→17, stats bar 13→14)
- **README.md** updated: added Julia notebook entry

## 2026-02-15: Website enhancements (cumulative from this session)

- **Julia language** added as key project language (hero, meta tags, filter button, CSS lang-tag)
- **Contributors section** replaced single-author section with 2-column grid (Carlos Mendez, Favio Leiva Cardenas)
- **Citation updated**: added Favio Leiva Cardenas as coauthor + BibTeX block
- **Visual refresh**: custom typography (Plus Jakarta Sans + Inter), animated gradient hero text, dot pattern background, stats bar with count-up animation, wave section dividers, enhanced card hover effects, scroll-reveal animations, contributor avatar glow

## 2026-02-15: Website content and structure updates

### People section reorganized

- Restructured into **Editors** (Carlos Mendez) and **Contributors** (Favio Leiva Cardenas)
- Navigation bar label changed from "Contributors" to "People"

### Citation reformatted

- Changed to open collection format: `Mendez C. (2026) Data Science for Development Studies: An Open Collection of Computational Notebooks and Apps. Zenodo.`
- BibTeX updated: `@collection` type, `author` field, year 2026
- Website URL added: `https://cmg777.github.io/ds4ds`
- BibTeX `url` field now points to website instead of DOI

### Community section added

- GitHub Discussions as community platform
- 5 bullet points encouraging participation (ask questions, share ideas, share notebooks, engage, welcome others)
- CTA button linking to `https://github.com/cmg777/ds4ds/discussions`

### Events section added

- Encourages participation in public training sessions and prototype design
- Events announced on Luma
- CTA button linking to `https://luma.com/cmg`

### Navigation updated

- Desktop, mobile, and footer nav now include: About, Notebooks, People, Community, Events, Resources

### README.md updated

- Title changed to "Data Science for Development Studies" with subtitle "An Open Collection of Computational Notebooks and Apps"
- Added Community, Events, and People sections
- Removed duplicate TBA entries
- Citation updated to match website

---

## Current project state

### Notebook inventory (14 notebooks + 3 external resources = 17 total)

| Section | Python | R | Julia | Apps/External | Total |
| --- | --- | --- | --- | --- | --- |
| Basic Statistics and Econometrics | 5 | 0 | 1 | 0 | 6 |
| Economic Growth and Development | 2 | 2 | 0 | 0 | 4 |
| Exploratory Data Analysis | 1 | 0 | 0 | 0 | 1 |
| Causal Inference | 0 | 2 | 0 | 1 app | 3 |
| Machine Learning | 1 | 0 | 0 | 1 app | 2 |
| Spatial Econometrics | 0 | 0 | 0 | 0 | TBA |
| Bayesian Econometrics | 0 | 0 | 0 | 0 | TBA |
| Feature Engineering and Geocomputation | 0 | 0 | 0 | 1 GEE | 1 |
| **Total** | **9** | **4** | **1** | **3** | **17** |

### File naming convention

All notebooks follow `{language}_{topic}.ipynb`:
- `python_` prefix for Python notebooks (9)
- `r_` prefix for R notebooks (4)
- `julia_` prefix for Julia notebooks (1)

### Website (index.html)

- Single-page site with Tailwind CSS, dark mode (default), responsive design
- Sections: Hero, Stats Bar, About, Notebooks (8 topic groups with search/filter), People (Editors + Contributors), Community, Events, Citation, Resources, Footer
- Navigation: About, Notebooks, People, Community, Events, Resources
- Google Fonts: Plus Jakarta Sans (headings), Inter (body), JetBrains Mono (code)
- Animations: gradient text, scroll-reveal, count-up stats, wave dividers, card hover, contributor glow
- Filter bar: All, Python, R, Julia, Apps
- Editor: Carlos Mendez | Contributor: Favio Leiva Cardenas
- Citation: APA + BibTeX — Mendez C. (2026), open collection format
- Community: GitHub Discussions (`https://github.com/cmg777/ds4ds/discussions`)
- Events: Luma (`https://luma.com/cmg`)
