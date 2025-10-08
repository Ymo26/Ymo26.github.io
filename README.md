# Yi Luo — Personal Website (GitHub Pages Template)

**Live site:** https://ymo26.github.io/  
A fast, reproducible academic portfolio showcasing projects in **ML forecasting**, **GIS & environmental health**, **econometrics**, and **sensor systems**.  
This repository is also a **template**: anyone can fork it and reuse `index.html` to build a personal website.

![screenshot placeholder](img/hero_screenshot.png)

---

---

## What This Is
- A minimal, framework-free **personal website** that emphasizes:  
  **clean data → careful methods → clear visuals → reproducibility**.
- Each project shows a **Basic description**, **Abstract**, and links to **Paper / Results / Code**.

---

## Features
- **Forecasting & ML** — classical vs. LSTM baselines; honest evaluation (nested CV, ablations, CIs).
- **Data Engineering** — leakage-safe preprocessing, imputation strategies, harmonized panels (EPA/NOAA/CDC).
- **GIS & Environment** — OSM + weather APIs; buffers; city-level comparisons for UHI.
- **Decision & Evaluation** — AHP survey design and robust benchmarking for tabular ML.
- **Reproducibility** — tidy repo, HTML/PDF artifacts, step-by-step pipelines.
- **Template-ready** — plain HTML/CSS/JS; easy to copy and customize.

---

## Selected Projects (Highlights)
- **Feature Engineering & AutoML Evaluations** — Compared curated, leakage-safe pipelines vs. AutoML on 30+ datasets; nested CV shows **AUROC gains of ~2–6pp**; reusable Jupyter templates.  
- **Environmental Determinants of Health (2000–2023)** — Harmonized county panel linking **PM2.5 / ozone / weather** to mortality; automated EPA/NOAA/CDC ingest, FIPS standardization, mapping; supports quasi-experimental designs.  
- **Decision Trees vs. Random Forests: Robustness on Noisy Tabular Data** — RF retains accuracy under **10–30%** label noise (−2–5pp vs. clean) while single trees degrade **8–15pp**; bootstrapped CIs and ablations.  
- **Urban Heat Island: Mapping & Microclimate Analysis** — OSM footprints + hourly weather; `sf` buffers; diagnostics show consistent **nocturnal warming** in dense cores; scalable cross-city comparisons.

---

## Tech Stack
**HTML/CSS/JS** • **Python** (pandas, matplotlib, scikit-learn, TensorFlow) • **R** (sf, dplyr, ggplot2) • **GitHub Pages**

