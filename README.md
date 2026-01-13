# SDVDs: Sonar Drowned Victims Datasets

![License](https://img.shields.io/badge/license-ODbL%20v1.0-brightgreen)  
**Version:** 2.0  
**Authors:**
  - [Jaszcz Antoni](https://orcid.org/0000-0002-8997-0331)
  - [Połap Dawid](https://orcid.org/0000-0003-1972-5979)
  - [Prokop Katarzyna](https://orcid.org/0000-0002-3830-6182)
  - Zaniewicz Grzegorz
  - Wawrzyniak Natalia

## Overview

**SDVDs (Sonar Drowned Victims Datasets)** is a collection of three annotated sonar image datasets designed for training segmentation models. The datasets are specifically tailored to assist in the detection and localization of drowned victims during search and recovery operations.  

Sonar images in this dataset simulate real-world scanning scenarios. Data was captured using a 1.8-meter metal effigy submerged in a river to simulate a human figure. bottom. This real-time mapping of the water bottom is vital in emergency situations, enabling quicker and more accurate victim recovery efforts.

Each subset includes:  
- **Sonar images**: Gray-scale 256x256x1 images
- **Binary masks**:  256x256x1 annotations marking the location of drowned victims

---

## Applications
The datasets are designed for researchers focusing on:  
- Sonar image segmentation.  
- Search and recovery systems for drowned victims.  
- Development of advanced machine learning models for sonar data analysis.  

---

## Dataset Structure
The SDVDs repository is organized as follows:
```
SDVDs/
│
├── SDVD/             # Original dataset
│   ├── images/
│   ├── masks/ 
│
├── CleanedSDVD/      # Improved masks
│   ├── images/
│   ├── masks/
│
├── ExtendedSDVD/     # Extended version (additional objects)
│   ├── images/
│   ├── masks/
│
├── LICENSE.txt       # ODbL license information
├── README.md         # This readme file
└── CITATION.cff      # Citation information
```
## Citation
Please use the following citations for this dataset:
- Dataset paper: A. Jaszcz, D. Połap, N. Wawrzyniak and G. Zaniewicz (2026). "Attention-Enhanced U-Net for Finding Drowned Victims Underwater Using Sonar Equipment," in IEEE Journal of Oceanic Engineering, doi: 10.1109/JOE.2025.3638526.
- Dataset repository: A. Jaszcz, et. al (2024). "SDVDs: Sonar Drowned Victim Datasets for image segmentation purposes" Version 2.0. Available at: https://github.com/AJaszcz/SDVDs-Sonar-Drowned-Victim-Datasets.

---