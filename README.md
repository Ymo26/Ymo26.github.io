# Yi Luo — Portfolio & Research Site
**Live site:** https://ymo26.github.io/

I build reproducible, policy-relevant analytics across **ML forecasting**, **GIS & environmental health**, and **econometrics**.  
This site collects my projects with clear **Basic description**, **Abstract**, and links to **papers/results/code**.

## What I do
- **Forecasting & ML:** compare classical models to LSTM baselines; honest evaluation (CV, ablations, CIs).
- **Data Engineering:** leakage-safe preprocessing, imputation strategies, harmonized panels (EPA/NOAA/CDC).
- **GIS & Environment:** OSM + weather APIs, buffers, and city-level comparisons for Urban Heat Island (UHI).
- **Decision & Evaluation:** AHP survey design and robust benchmarking for tabular ML.
- **Reproducibility:** tidy repos, HTML/PDF artifacts, and step-by-step pipelines.

## Selected projects (highlights)
- **Feature Engineering & AutoML Evaluations** — Compared curated, leakage-safe pipelines vs AutoML on 30+ datasets;  
  nested CV shows **AUROC gains of ~2–6pp**; produced reusable Jupyter templates.
- **Environmental Determinants of Health (2000–2023)** — Harmonized county panel linking **PM2.5/ozone/weather** to mortality;  
  automated EPA/NOAA/CDC ingest, FIPS standardization, and mapping; supports quasi-experimental designs.
- **Decision Trees vs. Random Forests: Robustness on Noisy Tabular Data** — Controlled experiments show RF maintains accuracy  
  under **10–30% label noise** (−2–5pp vs clean), while single trees degrade by **8–15pp**; bootstrapped CIs and ablations.
- **Urban Heat Island: Mapping & Microclimate Analysis** — OSM footprints + hourly weather;  
  buffers with `sf` and diagnostics show consistent **nocturnal warming** in dense cores; scalable cross-city comparisons.

## Quick links
- **Research:** `/research.html`
- **Papers:** `/paper/`
- **Results:** `/results/`
- **CV:** `/cv/Yi_Luo_CV.pdf`

## Built with
HTML/CSS/JS · Python (pandas, matplotlib, scikit-learn, TensorFlow) · R (sf, dplyr, ggplot2) · GitHub Pages
