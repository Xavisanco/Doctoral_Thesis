# Depression Detection in Speech Signal Using Machine Learning Models

Doctoral thesis documentation — Xavier Sánchez Corrales, University of Vic – Central University of Catalonia (UVic-UCC), 2026.

This repository contains the PDF documents and Jupyter notebooks accompanying the doctoral thesis _"Depression Detection in Speech Signal Using Machine Learning Models"_. The thesis comprises three original research contributions that progressively develop a sex-stratified, leakage-controlled pipeline for speech-based depression screening using adaptive modal decomposition (EMD and windowed VMD).

## Repository Contents

| Folder        | Description                                            |
| ------------- | ------------------------------------------------------ |
| `thesis/`     | Full thesis PDF                                        |
| `notebooks/`  | Jupyter notebooks for each contribution (see below)    |
| `appendices/` | Supplementary material included in the thesis appendix |

### Notebooks

- **Contribution 1** — EMD-based exploratory analysis of the male DAIC-WOZ cohort. Identifies discriminative IMFs via Gaussian-kernel overlap scoring.
- **Contribution 2** — Sex-stratified EMD feature extraction and classification. Extends the Gaussian-kernel selection criterion to both sexes and evaluates eight ML classifiers.
- **Contribution 3** — Windowed VMD pipeline with sex-stratified feature aggregation, nested cross-validation, Youden-threshold calibration, and four Winner's Curse bias-control experiments.

## Data Availability

**Audio data and clinical metadata are not included in this repository.** All experiments are based on the DAIC-WOZ corpus (_Distress Analysis Interview Corpus – Wizard of Oz_), which is protected and distributed under a data use agreement by the **University of Southern California (USC), Institute for Creative Technologies**. Access must be requested directly from USC ICT: <https://dcapswoz.ict.usc.edu/>.

No participant audio, transcripts, or PHQ-8 scores are redistributed here or in any other public location associated with this project.

## Publications

> Sánchez Corrales, X., Solé-Casals, J., Arroyo García, E., & Palao Vidal, D. (2025). _Analyzing Male Depression Using Empirical Mode Decomposition._ In Proceedings of the 18th International Joint Conference on Biomedical Engineering Systems and Technologies (BIOSIGNALS), pp. 886–892. SciTePress. DOI: [10.5220/0013157600003911](https://doi.org/10.5220/0013157600003911)

> Sánchez Corrales, X., & Solé-Casals, J. (2025). _Feature extraction from speech signals using empirical mode decomposition for depression detection: A comparative study with machine learning models._ Computer Speech & Language. DOI: [10.1016/j.csl.2025.101898](https://doi.org/10.1016/j.csl.2025.101898)

> Sánchez Corrales, X., Sun, L., Jia, H., & Solé-Casals, J. (submitted). _Windowed Variational Mode Decomposition with Gaussian-Kernel Mode Selection for Sex-Stratified Speech-Based Depression Screening._ Computer Methods and Programs in Biomedicine. Preprint available in the `appendices/` folder.

## Usage Restrictions

The code, notebooks, and documents in this repository are provided **for academic and research purposes only**. Commercial use, including incorporation into commercial products or services, is **not permitted** without prior written consent from the author.

## Author

**Xavier Sánchez Corrales**
Data and Signal Processing Research Group, University of Vic – Central University of Catalonia (UVic-UCC), Vic, Spain
xavier.sanchez.corrales@uvic.cat
ORCID: [0009-0002-4335-6851](https://orcid.org/0009-0002-4335-6851)
