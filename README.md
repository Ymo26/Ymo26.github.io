# Yi Luo — Portfolio & Research Site

**Live site:** https://ymo26.github.io/

I build reproducible, policy-relevant analytics across **ML forecasting**, **GIS & environmental health**, and **econometrics**.  
This site presents each project with a **Basic description**, **Abstract**, and links to **papers / results / code**.

---

## Table of Contents
- [Features](#features)
- [Selected Projects (Highlights)](#selected-projects-highlights)
- [Built With](#built-with)
- [Folder Structure](#folder-structure)
- [Quick Start (Use This as Your Template)](#quick-start-use-this-as-your-template)
- [Local Development](#local-development)
- [Deployment (GitHub Pages)](#deployment-github-pages)
- [Content Guidelines](#content-guidelines)
- [License](#license)
- [Contact](#contact)

---

## Features
- **Forecasting & ML** — compare classical models to LSTM baselines; honest evaluation (CV, ablations, CIs).
- **Data Engineering** — leakage-safe preprocessing, imputation strategies, harmonized panels (EPA/NOAA/CDC).
- **GIS & Environment** — OSM + weather APIs, buffers, and city-level comparisons for UHI analysis.
- **Decision & Evaluation** — AHP survey design, robust benchmarking for tabular ML.
- **Reproducibility** — tidy repos, HTML/PDF artifacts, step-by-step pipelines.

---

## Selected Projects (Highlights)

- **Feature Engineering & AutoML Evaluations**  
  Compared curated, leakage-safe pipelines vs. AutoML on 30+ datasets; nested CV shows **AUROC gains of ~2–6pp**; reusable Jupyter templates.

- **Environmental Determinants of Health (2000–2023)**  
  Harmonized county-level panel linking **PM2.5 / ozone / weather** to mortality; automated EPA/NOAA/CDC ingest, FIPS standardization, and mapping; supports quasi-experimental designs.

- **Decision Trees vs. Random Forests: Robustness on Noisy Tabular Data**  
  Controlled experiments show RF retains accuracy under **10–30%** label noise (−2–5pp vs. clean) while single trees degrade by **8–15pp**; bootstrapped CIs and ablations.

- **Urban Heat Island: Mapping & Microclimate Analysis**  
  OSM footprints + hourly weather; buffers with `sf`; diagnostics show consistent **nocturnal warming** in dense cores; scalable cross-city comparisons.

---

## Built With
HTML/CSS/JS • Python (pandas, matplotlib, scikit-learn, TensorFlow) • R (sf, dplyr, ggplot2) • GitHub Pages

---

## Folder Structure
