# STATS/DATASCI 631: Time Series Reading Notes

[![Course](https://img.shields.io/badge/Course-STATS%2FDATASCI%20631-blue)](https://ionides.github.io/531w25/631)
[![Institution](https://img.shields.io/badge/Institution-University%20of%20Michigan-yellow)](https://lsa.umich.edu/stats)
[![Instructor](https://img.shields.io/badge/Instructor-Edward%20Ionides-green)](https://ionides.github.io/)

## About This Repository

This repository contains my reading notes and summaries for **STATS/DATASCI 631: Modeling and Analysis of Time Series Data**, taught by Professor Edward Ionides at the University of Michigan. The course provides advanced coverage of statistical methods for time series analysis, building on foundational concepts from STATS/DATASCI 531.

## Course Information

- **Course Title**: Modeling and Analysis of Time Series Data
- **Course Number**: STATS/DATASCI 631
- **Instructor**: [Professor Edward Ionides](https://ionides.github.io/)
- **Institution**: University of Michigan, Department of Statistics
- **Semester**: Winter 2025 (Week 1)

### Course Focus

The course covers advanced topics in time series analysis with applications in:
- Ecology and environmental science
- Epidemiology and public health
- Health economics
- Partially observed stochastic dynamic systems (POMP models)

## Reading Notes

### Week 1

#### 📄 [Akaike (1974) - A New Look at the Statistical Model Identification](akaike_notes.qmd)

**Citation**: Akaike, H. (1974). A new look at the statistical model identification. *IEEE Transactions on Automatic Control*, AC-19(6), 716-723.

**Topics Covered**:
- The Akaike Information Criterion (AIC)
- Kullback-Leibler divergence and information theory
- Maximum likelihood estimation and model selection
- Connection to Final Prediction Error (FPE) and Mallows' Cp
- Applications to autoregressive time series models

**Key Contribution**: Introduction of AIC as a principled approach to model selection that balances goodness-of-fit with model complexity:

```
AIC = -2 log L(θ̂) + 2k
```

where `L(θ̂)` is the maximum likelihood and `k` is the number of parameters.

**View Notes**:
- [HTML version](akaike_notes.html) (rendered)
- [Quarto source](akaike_notes.qmd) (source with LaTeX)

---

## Structure

Each reading note includes:

- **Paper Overview**: Citation, main contributions, and context
- **Key Mathematical Foundations**: Core theoretical results with derivations
- **Applications**: Numerical examples and practical implementations
- **Critical Insights**: Advantages, limitations, and connections to other methods
- **References**: Related literature and further reading

## Tools & Technologies

- **Quarto**: For creating reproducible, publication-quality documents
- **LaTeX**: For mathematical notation and equations
- **Mermaid**: For diagrams and flowcharts
- **HTML/CSS**: Custom styling with the Cosmo theme

## About the Author

**Kunyang He**
Graduate Student, Statistics/Data Science
University of Michigan

## Resources

### Course Materials
- [Professor Ionides' Homepage](https://ionides.github.io/)
- [STATS 531 Course Materials (related undergraduate/masters course)](https://ionides.github.io/531w22/)

### Related Courses
- **STATS/DATASCI 531**: Analysis of Time Series (prerequisite/related course)
- **STATS 620**: Theory of Statistics
- **STATS 810**: Advanced Probability and Statistics

### Key References

1. **Akaike, H. (1974)**. A new look at the statistical model identification. *IEEE Transactions on Automatic Control*, AC-19(6), 716-723.
2. **Burnham, K. P., & Anderson, D. R. (2002)**. *Model Selection and Multimodel Inference*. Springer.
3. **Kullback, S. (1959)**. *Information Theory and Statistics*. Wiley.
4. **Shumway, R. H., & Stoffer, D. S. (2017)**. *Time Series Analysis and Its Applications*. Springer.

## License

This work is for educational purposes. All reading notes are original summaries and interpretations of published academic papers.

---

## Contributing

These are personal study notes, but if you find errors or have suggestions, feel free to open an issue or reach out!

## Acknowledgments

Special thanks to Professor Edward Ionides for his excellent teaching and for making course materials publicly available.

---

**Last Updated**: January 13, 2025
**Current Status**: Week 1 - Active
