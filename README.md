# Effect of Water and Shade Access on Cattle Behavior and Thermal Comfort

<div align="center">
  <img src="figures/study_area.png" alt="Silvopastoral paddocks at Ressacada Experimental Farm, UFSC" width="400"/>
</div>

## 📜 Study Overview

This research, conducted at the Laboratory of Applied Ethology and Animal Welfare (LETA/UFSC), evaluated how the combination of shade availability and water access affects the behavior and thermal comfort of Braford and Jersey cows managed under Voisin Rational Grazing in a silvopastoral system.

Key findings include:

- **Shade increased daytime grazing time** in S+W+ compared to all other treatments (*p* < 0.05).
- **Water restriction altered drinking dynamics** — restricted animals showed longer drinking times and more sips per event.
- **Unshaded paddocks reached critical ITGU levels (>84)** for up to 6 hours daily, while shaded paddocks remained below the alert threshold.
- **Body surface temperatures were significantly higher** in unshaded treatments, particularly at the flanks.
- **Nocturnal compensatory grazing** was observed in the S+W− treatment.

**Manuscript Status**: In preparation — *Applied Animal Behaviour Science* (Elsevier)

**Website**: [jpdonadio.github.io/water-shade-cattle-behavior](https://jpdonadio.github.io/water-shade-cattle-behavior)

---

## 🗂️ Repository Structure

```
water-shade-cattle-behavior/
├── data/                            # See data/README.md for access instructions
├── figures/                         # Generated plots and maps
├── manuscript/
│   ├── Prettoetal_water_shade.qmd   # Full manuscript
│   └── references.bib               # Bibliography
├── docs/                            # Rendered Quarto website (GitHub Pages)
├── index.qmd                        # Website homepage
├── methods.qmd                      # Methods page
├── results-daytime.qmd              # Daytime behavior results + analysis
├── results-nighttime.qmd            # Nighttime behavior results + analysis
├── results-drinking.qmd             # Drinking behavior results + analysis
├── results-thermal.qmd              # Thermal comfort results + analysis
├── results-thermography.qmd         # Thermography results + analysis
├── findings.qmd                     # Key findings page
├── about.qmd                        # About page
├── _quarto.yml                      # Quarto website configuration
├── custom.scss                      # Custom theme
├── LICENSE
└── README.md
```

---

## 🧪 Experimental Design

Thirty-two cows (16 Braford, 16 Jersey) were assigned to four treatments in a 4 × 4 Latin square design, managed under Voisin Rational Grazing at the Ressacada Experimental Farm, UFSC, Florianópolis, Brazil (December 2021 – April 2022).

| Treatment | Shade | Water | Description |
|-----------|-------|-------|-------------|
| **S+W+** | ✅ | *ad libitum* 24h | Shade + free water |
| **S+W−** | ✅ | Restricted 1h/day | Shade + restricted water |
| **S−W+** | ❌ | *ad libitum* 24h | No shade + free water |
| **S−W−** | ❌ | Restricted 1h/day | No shade + restricted water |

Behavioral scans were recorded every 10 minutes across full 24-hour cycles. Thermographic images were taken at 10:00, 13:00, and 16:00h. Thermal comfort indices (ITGU, WBGT, TLR) were recorded hourly from 09:00 to 18:00h.

Animal procedures were approved by the Ethics Committee on Animal Use (CEUA/UFSC), Protocol 857122042.

---

## 🛠️ Skills & Tools

- **Statistical Analysis**: GLMMs (Gaussian and Poisson), random effects (animal, day, hour), AIC model comparison
- **Data Visualization**: Interactive time-series, thermographic heatmaps, treatment comparison plots
- **Reproducibility**: Full analysis embedded in Quarto pages, documented data, rendered website
- **Domain Expertise**: Cattle ethology, thermal physiology, silvopastoral systems, Voisin Rational Grazing
- **Tools**: ![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white) ![RStudio](https://img.shields.io/badge/RStudio-75AADB?logo=rstudio&logoColor=white) ![Quarto](https://img.shields.io/badge/Quarto-1976D2?logo=quarto&logoColor=white) ![lme4](https://img.shields.io/badge/lme4-1.1--35-8B9DC3) ![tidyverse](https://img.shields.io/badge/tidyverse-1.3-1D6F42) ![ggplot2](https://img.shields.io/badge/ggplot2-3.4-3A7CB8) ![plotly](https://img.shields.io/badge/plotly-4.10-3D4DB7) ![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)

---

## 👥 Authors & Contributions

| Name | Affiliation | Contributions |
|------|-------------|---------------|
| **Fidel de Souza Pretto**<br>(F.S. Pretto) | Graduate Program in Agroecosystems, UFSC | • Study conception and design<br>• Field data collection<br>• Original draft preparation |
| **João Pedro Donadio**<br>(J.P. Donadio) | Graduate Program in Animal Science, UNESP Botucatu | • Data analysis and visualization<br>• Reproducible workflow<br>• Manuscript preparation |
| **Luiz Carlos Pinheiro Machado Filho**<br>(L.C. Pinheiro Machado Filho) | LETA, Department of Zootechny and Rural Development, UFSC | • Study conception and design<br>• Critical manuscript revision<br>• Supervision |

**Correspondence**: pinheiro.machado@ufsc.br

---

## 🙏 Acknowledgments

| Category | Details |
|----------|---------|
| **Funding** | CAPES — Master's scholarship awarded to F.S. Pretto |
| **Institutional** | Laboratory of Applied Ethology and Animal Welfare (LETA), Federal University of Santa Catarina (UFSC) |
| **Field support** | Ressacada Experimental Farm (FER–UFSC) staff |
| **Ethics approval** | CEUA/UFSC, Protocol 857122042 |
