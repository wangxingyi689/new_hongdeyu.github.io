---
title: "Predicting Magnetic Coupling and Spin-Polarization Energy in Triangulene Analogues"
authors:
- Hongde Yu
- Jianwei Sun
- Thomas Heine*
date: "2024-06-01T00:00:00Z"
doi: "10.1021/acs.jctc.3c00175"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Science Advances, 10*(40)"
publication_short: ""

abstract: Triangulene and its analogue metal-free magnetic systems have garnered increasing attention since their discovery. Predicting the magnetic coupling and spin-polarization energy with quantitative accuracy is beyond the predictive power of today’s density functional theory (DFT) due to their intrinsic multireference character. Herein, we create a benchmark dataset of 25 magnetic systems with nonlocal spin densities, including the triangulene monomer, dimer, and their analogues. We calculate the magnetic coupling (J) and spin-polarization energy (ΔEspin) of these systems using complete active space self-consistent field (CASSCF) and coupled-cluster methods as high-quality reference values. This reference data is then used to benchmark 22 DFT functionals commonly used in material science. Our results show that, while some functionals consistently correctly predict the qualitative character of the ground state, achieving quantitative accuracy with small relative errors is currently not feasible. PBE0, M06-2X, and MN15 are predicting the correct electronic ground state for all systems investigated here and also have the lowest mean absolute error for predicting both ΔEspin (0.34, 0.32, and 0.31 eV) and J (11.74, 12.66, and 10.64 meV). They may therefore also serve as starting points for higher-level methods such as the GW or the random phase approximation. As other functionals fail for the prediction of the ground state, they cannot be recommended for metal-free magnetic systems.

# Summary. An optional shortened abstract.
summary: We developed a benchmark dataset comprising 25 magnetic systems with nonlocal spin densities, including triangulene monomers, dimers, and their analogues. This work highlighted the importance of the choice of DFT functional.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://pubs.acs.org/doi/epdf/10.1021/acs.jctc.3c00175?ref=article_openPDF

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**]()'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
