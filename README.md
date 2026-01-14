# STATS 631 Reading Notes

Reading notes for **Modeling and Analysis of Time Series Data** (STATS/DATASCI 631)
Instructor: [Edward Ionides](https://ionides.github.io/) • University of Michigan • Winter 2025

## About

This repository contains detailed reading notes from the seminal papers in time series analysis. The course covers advanced statistical methods with applications in ecology, epidemiology, health economics, and partially observed stochastic dynamic systems (POMP models).

Each note includes:
- Mathematical foundations and key derivations
- Connections to modern methods
- Numerical examples and applications
- Critical insights and limitations

## Reading Notes

### Week 1

**Akaike (1974)** - A New Look at the Statistical Model Identification
[[HTML](akaike_notes.html)] [[Quarto](akaike_notes.qmd)]

Introduction of the Akaike Information Criterion (AIC) for model selection:
```
AIC = -2 log L(θ̂) + 2k
```

**Key topics:**
- Kullback-Leibler divergence and information theory
- Fisher information matrix and asymptotic distribution of MLE
- Bias correction in model selection (the +2k penalty)
- Connection to Final Prediction Error (FPE) and Mallows' Cp
- Applications to autoregressive and moving average models

**Why it matters:** AIC revolutionized model selection by providing a principled, automatic approach that balances model fit with complexity, eliminating the need for arbitrary significance levels in hypothesis testing.

## Resources

### Course Materials
- [Professor Ionides' Homepage](https://ionides.github.io/)
- [STATS 531 Course Materials](https://ionides.github.io/531w22/) (related course)

### Key References
- Burnham & Anderson (2002). *Model Selection and Multimodel Inference*
- Shumway & Stoffer (2017). *Time Series Analysis and Its Applications*

---

*Last updated: January 13, 2025*
