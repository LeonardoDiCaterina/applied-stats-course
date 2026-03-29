# Applied Statistics — Weekly R Workshops

Welcome to the central repository for our Applied Statistics R Workshops! 

This repository contains all the code, data, and templates you will need for our weekly lab sessions. We will be using real-world data to apply the statistical concepts covered in lectures using modern R and RStudio.

##️ How This Repository Works (The "Time-Release" Format)

To help you practice writing code yourself, workshop materials are released in two stages:

1. **Before Class (The Template):** A blank `student_template.Rmd` file will be uploaded. This contains the structure of the workshop and empty code chunks. You will fill these in live during the session.
2. **After Class (The Reference):** A complete `student_reference.Rmd` file will be uploaded. This contains all the correct code, outputs, and economic interpretations for you to keep as a permanent study guide.


---

##  Workshop Schedule

| Week | Topic | Key Concepts & R Functions |
| :--- | :--- | :--- |
| **1** | **R Refresher** | Loading data, running `lm()`, interpreting the summary, setting up R Markdown/Quarto. |
| **2** | **Visualizing Errors** | Plotting residuals, Cook's Distance, calculating VIF, robust standard errors. |
| **3** | **Transforming Data** | Using `log()` and `I(x^2)` in regressions, plotting non-linear curves in `ggplot2`. |
| **4** | **Marginal Effects** | Running interactive models in R, using `ggeffects` to plot slope changes. |
| **5** | **Logit Models** | Running `glm(family=binomial)`, translating Log-Odds to Odds Ratios. |
| **6** | **Advanced Inference** | Running `aov()`, Tukey's HSD post-hoc tests, applying `p.adjust()`. |
| **7** | **Factor Analysis** | Running PCA (`prcomp`) and EFA (`factanal`), interpreting scree plots and loadings. |
| **8** | **Clustering** | Scaling data, running `hclust` and `kmeans`, finding the Elbow Method. |
| **9** | **Time Series** | Creating `ts` objects, Dickey-Fuller tests, using `auto.arima()` to plot predictions. |
| **10** | **Panel Data** | Using the `plm` package, running a Fixed Effects model on a country-year dataset. |
| **11** | **Instrumental Variables** | Running 2SLS using `ivreg()`, testing instrument relevance (First Stage F-test). |
| **12** | **Final Assessment** | Unseen Dataset: Choosing the correct advanced model, running code, verifying assumptions, writing the report. |

---
*Note: Ensure you have the latest versions of R and RStudio Desktop installed before Week 2.*