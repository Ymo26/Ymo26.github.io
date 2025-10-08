# Yi Luo — Personal Website (GitHub Pages Template)

**Live Site:** [https://ymo26.github.io/](https://ymo26.github.io/)  
A clean, reproducible academic portfolio showcasing projects in **Machine Learning**, **GIS & Environmental Health**, **Econometrics**, and **Data Science**.  
Built with **HTML/CSS/JS** and deployed using **GitHub Pages**.  
You can **fork this repository** and use it as your personal website template.

---

## 🧭 Table of Contents
- [About This Project](#about-this-project)
- [Features](#features)
- [Selected Projects](#selected-projects)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Prerequisites](#prerequisites)
- [Quick Start — Use This as Your Own Site](#quick-start--use-this-as-your-own-site)
- [Local Development](#local-development)
- [Usage & Customization (Step-by-Step)](#usage--customization-step-by-step)
- [Deployment (GitHub Pages)](#deployment-github-pages)
- [Content Guidelines & Best Practices](#content-guidelines--best-practices)
- [Contributing](#contributing)
- [License](#license)
- [Roadmap / Known Issues](#roadmap--known-issues)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

## 🧩 About This Project
This site highlights my academic and technical work with a focus on **clarity, transparency, and reproducibility**.  
Each project section includes:
- **Basic description** — a short summary of the project’s purpose and scope.  
- **Abstract** — methods, datasets, and key results.  
- **Links** — to paper PDFs, output results, or GitHub repositories.

---

## 🚀 Features
- **Forecasting & ML:** Compare classical models with LSTM baselines; evaluate with nested CV and ablation studies.  
- **Data Engineering:** Leakage-safe preprocessing, missing data imputation, harmonized EPA/NOAA/CDC datasets.  
- **GIS & Environmental Analysis:** City-level heat island analysis using OSM + weather APIs.  
- **Decision & Evaluation:** AHP survey design, robust benchmarking of tabular ML models.  
- **Reproducibility:** Organized structure, HTML/PDF artifacts, and versioned outputs.  
- **Template-ready:** Lightweight, no frameworks — easy to copy, edit, and publish.

---

## 🧪 Selected Projects
- **Feature Engineering & AutoML Evaluations** — Compared curated, leakage-safe pipelines vs AutoML defaults on 30+ datasets; achieved **AUROC gains of 2–6pp**; built reproducible Jupyter templates.  
- **Environmental Determinants of Health (2000–2023)** — Linked **PM2.5/ozone/weather** to mortality across 3,000+ counties; automated EPA/NOAA/CDC integration; supports quasi-experimental research.  
- **Decision Trees vs Random Forests: Robustness on Noisy Data** — RF retained accuracy under **10–30% label noise**; bootstrapped CIs confirmed robustness vs single trees.  
- **Urban Heat Island: Mapping & Microclimate Analysis** — Combined **OSM building footprints** and **hourly weather**; revealed consistent **nocturnal warming** patterns in dense cores.

---

## 🛠️ Tech Stack
**Frontend:** HTML, CSS, JavaScript  
**Data Tools:** Python (pandas, scikit-learn, TensorFlow), R (sf, dplyr, ggplot2)  
**Hosting:** GitHub Pages

---

## 📁 Folder Structure
.
├─ css/ # Stylesheets
├─ js/ # Optional scripts or animations
├─ img/ # Images, logos, screenshots
├─ cv/ # CV/Resume PDFs
├─ paper/ # Papers and writeups (PDF)
├─ results/ # Outputs: plots, HTML reports, tables
├─ index.html # Landing page (template-ready)
├─ research.html # (Optional) Research detail page
└─ README.md


---

## ⚙️ Prerequisites
- A **GitHub account**  
- A text editor (recommended: **VS Code**)  
- *(Optional)* Python 3 for local preview

---

## 🏁 Quick Start — Use This as Your Own Site

1. **Fork** this repository.  
2. Rename your fork to **`<username>.github.io`** (replace `<username>` with your GitHub username).  
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch* and **Branch** to `main`.  
4. Wait for the deployment to finish, then visit:  
   👉 `https://<username>.github.io`

---

## 💻 Local Development

### Option A — Python Simple Server
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## 🧩 Usage & Customization (Step-by-Step)
Use the block below as a **project card** pattern inside your `index.html` (or `research.html`).  
Replace placeholders with your info.

```html
<article class="proj">
  <h3>Project Title <span class="tag">Category or Course</span></h3>
  <div class="meta">Stack/Methods: Python (pandas, scikit-learn), cross-validation</div>

  <p><span class="label">Basic description:</span>
    1–3 sentences summarizing the goal and what you built.
  </p>

  <p><span class="label">Abstract:</span>
    4–6 sentences on data, methods, key results, and what’s novel.
  </p>

  <p class="links">
    <a href="paper/Project_Title.pdf" target="_blank">Paper (PDF)</a> ·
    <a href="results/Project_Title_outputs.html" target="_blank">Results</a> ·
    <a href="https://github.com/YOURNAME/ProjectRepo" target="_blank">Code Repository</a>
  </p>
</article>

Step 3 — Organize Assets

Store images in img/, papers in paper/, results in results/, and your CV in cv/.

Use consistent names (e.g., uhi-2025-map.png).

Step 4 — Navbar Example

<nav>
  <a href="index.html">Home</a>
  <a href="research.html">Research</a>
  <a href="cv/Yi_Luo_CV.pdf" target="_blank">CV</a>
  <a href="paper/">Papers</a>
  <a href="results/">Results</a>
</nav>
```
---
## 🚀 Deployment (GitHub Pages)

Push changes to main to automatically deploy your updated site.

git add -A
git commit -m "Update site content"
git push origin main


---
## 🧾 Content Guidelines & Best Practices

✅ Filenames: Use kebab-case (e.g., urban-heat-island-2025.png).
✅ Accessibility: Add descriptive alt text for all images.
✅ Performance: Compress large images and PDFs.
✅ Consistency: Each project = Basic Description + Abstract + Links.
✅ Simplicity: Short paragraphs, bullet points, and clear formatting.

---
## 🤝 Contributing

You can improve this template by:

Opening an Issue to describe your idea or problem.

Forking this repo and creating a feature branch.

Submitting a Pull Request with clear descriptions and screenshots.


---
## ⚖️ License

```Template Code: MIT License
Content (text, images, papers): © Yi Luo — All rights reserved unless noted.
MIT License

Copyright (c) Yi Luo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```
---
## 🧭 Roadmap / Known Issues

 Add dark mode toggle

 Add search/filter for projects

 Optimize for mobile viewing

 Add analytics support (optional)
 
 ---


## 📬 Contact

Website: https://ymo26.github.io/

Email: Luo45802@outlook.com

LinkedIn: https://www.linkedin.com/in/yi-luo-59b185338/

 ---

## 🙏 Acknowledgements

Open data sources: EPA, NOAA, CDC, OpenStreetMap

Inspired by academic portfolio layouts and the GitHub Pages community

✅ **How to use:**  
1. Copy this entire markdown block.  
2. Paste it into your GitHub README editor.  
3. Click **“Commit changes”** — GitHub will render it like your screenshot (with clean sections, headers, and boxes).

 ---
 
