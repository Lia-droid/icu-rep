##  Associated Publication

This repository accompanies the article:

**"Predicting Public Intensive Care Unit Mortality and Hospitalization Using Data: An Evaluation of Brazil's Largest COVID-19 Epidemiological Dataset"**  
*Intensive & Critical Care Nursing* (Elsevier, 2026)  

🔗 Article link: https://www.sciencedirect.com/science/article/pii/S0964339726000315?via%3Dihub  
🔗 Article DOI: https://doi.org/10.1016/j.iccn.2026.104363  

##  Citation and Reproducibility

If you use this repository, please cite both the article and the Zenodo archive:

**Article:**

Graça, L., et al. (2026). *Predicting Public Intensive Care Unit Mortality and Hospitalization Using Data: An Evaluation of Brazil's Largest COVID-19 Epidemiological Dataset*. Intensive & Critical Care Nursing.  
https://doi.org/10.1016/j.iccn.2026.104363  

**Code and Materials (Zenodo):**

Graça, L. (2026). *ICU mortality prediction – reproducible code and materials*. Zenodo.  
https://doi.org/10.5281/zenodo.18064988  

This repository is organized to ensure full transparency and reproducibility
of the ICU cohort construction and analysis pipeline.

###  Data
The original INFLUD/SRAG datasets are publicly available via OpenDataSUS and
are not redistributed in this repository due to size and licensing constraints.

Processed and intermediate data used in the analyses are generated locally
following the procedures described in the documentation.

➡️ Data access and preprocessing instructions:
[data/](data/)

---

###  Notebooks
The final analysis and reproducible workflow used for the manuscript submission
are provided as Jupyter notebooks.

➡️ Final submission notebook:
[notebooks/evolucao_V12_git.ipynb](notebooks/evolucao_V12_git.ipynb)

---

###  Documentation
Detailed methodological documentation, integration manuals, and supporting
materials are available in the documentation directory.

➡️ [Project Documentation](docs/)

---

###  Figures
Key figures and flowcharts describing the ICU cohort construction and study
workflow are available here:

➡️ [figures/](figures/)

##  Contributing

Contributions are welcome. If you would like to report issues, suggest
improvements, or contribute code, please see
[CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

###  BibTeX

```bibtex
@article{graca2026icu,
  title={Predicting Public Intensive Care Unit Mortality and Hospitalization Using Data: An Evaluation of Brazil's Largest COVID-19 Epidemiological Dataset},
  author={Graça, Lia and others},
  journal={Intensive \& Critical Care Nursing},
  year={2026},
  doi={10.1016/j.iccn.2026.104363}
}

@software{graca2026zenodo,
  author       = {Graça, Lia},
  title        = {ICU mortality prediction – reproducible code and materials},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18064988}
}

