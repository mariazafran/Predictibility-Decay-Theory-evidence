# Predictability Decay Analysis (Colab Notebook)

## Overview
This project explores whether financial market predictability is stable or short-lived.  
Using FTSE 100 data (2005–2024), the analysis shows that predictability follows a **lifecycle** — it emerges, reaches a peak, and then rapidly declines.

---

## What this notebook does
- Downloads FTSE 100 market data  
- Builds a rolling regression model using lagged returns  
- Measures predictability using out-of-sample R²  
- Tracks how predictability changes over time  

---

## Key Results
- Predictability exists but is **inconsistent** (peak ≈ 0.29)  
- Predictability **declines sharply** after reaching its peak  
- Half-life ≈ **5 periods** → very short-lived  
- Faster decay observed during **high-volatility periods**  

---

##  Core Insight
> Predictability is **temporary and self-destructive** — once patterns are detected, markets adapt and eliminate them.

---

## How to Run
1. Open the notebook in Google Colab  
2. Run all cells step by step  
3. Outputs include:
   - Predictability (R²) over time  
   - Smoothed trend visualization  
   - Decay and half-life metrics  

---


## Citation

If you use this work, please cite:

Bibi, M. (2026). *Predictibility Decay Analysis*. GitHub repository.  
Available at: https://github.com/mariazafran/Predictibility-Decay-Theory-evidence  

## Code and Resources

The complete codebase is available at:  
https://github.com/mariazafran/Predictibility-Decay-Theory-evidence  

The specific notebook used in this analysis:  
https://github.com/mariazafran/Predictibility-Decay-Theory-evidence/blob/main/Predictibility_Decay_Analysis.ipynb  

Google Colab version:  
https://colab.research.google.com/drive/1Xs-PDodcbZHMT6tqImUd7ZGO5djUDe89?usp=sharing

---

## Disclaimer
This work is for academic and research purposes only.  
It does not constitute financial or investment advice.

---

## © License
© 2026 Maria Bibi. All Rights Reserved.

This repository contains original research and intellectual contributions.  
Unauthorized use, reproduction, or distribution is prohibited.

Any use of this work must include proper citation.

For permissions: mariazafran1996@gmail.com
