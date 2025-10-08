# Ymo26.github.io
**Naming tips**
- Use kebab-case and include dates when helpful: `UHI-2025-results-plot1.png`
- Keep PDFs small; compress images for faster loads.

---

## 🧭 How to Add a New Research Project
Each project card shows **Basic Description** and **Abstract**, plus links to outputs.

1. **Upload assets**
   - Put figures in `img/`, code snippets (if any) in `results/`, and papers in `paper/`.
2. **Edit the Research page**
   - Open your Research page (e.g., `research.html` if you split it; otherwise section within `index.html`).
   - Add a new block following this pattern:

```html
<article class="proj">
  <h3>Project Title <span class="tag">Category or Course</span></h3>
  <div class="meta">Stack/Methods: Python (pandas, matplotlib), AHP, survey design</div>

  <p><span class="label">Basic description:</span>
    1–3 sentences summarizing the goal and what you built.
  </p>

  <p><span class="label">Abstract:</span>
    4–6 sentences: data, methods, key results, and what’s novel.
  </p>

  <p class="links">
    <a href="paper/Project_Title_2025.pdf" target="_blank">Paper</a> ·
    <a href="results/Project_Title_outputs.html" target="_blank">Outputs</a> ·
    <a href="https://github.com/Ymo26/ProjectRepo" target="_blank">Code (GitHub)</a>
  </p>
</article>
