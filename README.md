# 🎵 Music in the Digital Era: Predicting Chart Success Across Digital Platforms

This repository contains all the code notebooks associated with the dissertation thesis:

> **"Music in the Digital Era: Predicting Chart Success Across Digital Platforms"**  
> Faculty of Administration and Business – University of Bucharest  
> Business Analytics Specialization  
> **Author:** Rusu Andrei – andrei.rusu1@s.unibuc.ro  
> **Coordinator:** Prof. Bogdan Oancea, PhD – bogdan.oancea@faa.unibuc.ro  
> **Year:** 2025  

## 📄 Abstract

The digital transformation of music has created complex multi-platform ecosystems where success patterns remain poorly understood.  
This study develops a framework for predicting Billboard Hot 100 chart success through cross-platform performance analysis and temporal relationship modeling.  
Using weekly chart data from six platforms across 2024, the research employs Dynamic Time Warping clustering, Granger causality analysis, and Long Short-Term Memory neural networks not merely to quantify the visible transfer of success between platforms, but to uncover hidden temporal patterns and sequential relationships in cross-platform performance, independent of Billboard's own weighting rules.  
This study aims to go beyond the official chart methodology to identify latent connections and influences that may shape Hot 100 trajectories in ways not immediately apparent from published chart outcomes.  
The analysis identifies six distinct trajectory patterns in chart performance with high classification accuracy.  
Granger causality testing reveals temporal hierarchies where certain platforms serve as leading indicators with specific lag periods, while radio shows diminished predictive power.  
The integrated multi-platform approach demonstrates superior performance compared to baseline models, though historical chart performance dominates prediction over cross-platform relationships.  
The findings provide practical guidance for industry stakeholders while advancing understanding of digital content diffusion in multi-platform environments.

---

## 🧾 Repository Structure

Each notebook corresponds to a specific part of the research pipeline:

| File | Description |
|------|-------------|
| `hot100.ipynb` | Processes Billboard Hot 100 chart data and aligns it temporally with other platform datasets |
| `radio.ipynb` | Processes Billboard Radio Songs chart data and aligns it temporally with other platform datasets |
| `sales.ipynb` | Processes Billboard Digital Sales chart data and aligns it temporally with other platform datasets |
| `streaming.ipynb` | Processes Billboard Streaming Songs chart data and aligns it temporally with other platform datasets |
| `clean.ipynb` | Cleans all input datasets, fills missing values, and prepares data for merging |
| `merge.ipynb` | Performs multi-source merges between datasets and applies validation rules |
| `combine_all.ipynb` | Combines all cleaned and merged datasets into a master dataframe for modeling |
| `eda.txt` | Conducts exploratory data analysis (EDA) across all features and charts |
| `clustering.txt` | Applies DTW-based trajectory clustering to identify common chart performance patterns |
| `causality.txt` | Runs Granger causality analysis to determine predictive relationships between platforms |
| `prediction.txt` | Trains forecasting models (LSTM) to predict Hot 100 chart positions based on cross-platform dynamics |

---

## ⚠️ License

This project currently has **no license applied**.  
All rights are reserved until public defense of the dissertation.  
Please do not reuse or distribute without explicit permission.

