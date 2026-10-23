---
layout: default
title: Oscar Carranza — Data Science Portfolio
---

# Oscar Carranza

I am developing reproducible data-analysis and visualization projects as part of my data-science studies. I focus on making assumptions, uncertainty and limitations visible alongside results.

**Technical skills demonstrated here:** Python, NumPy, pandas, Matplotlib, simulation, statistical visualization and reproducible project organization.

## Project: How sample size changes uncertainty in a mean

**Research question:** How does increasing sample size change the variability of a sample mean when individual observations are right-skewed?

![Individual observations and distributions of sample means](assets/distributions.png)

The simulated individual observations are right-skewed, while the averages become more concentrated near 10 as sample size increases. The empirical standard error decreases from 4.507 at n=5 to 1.001 at n=100.

![Standard errors compared with the theoretical formula](assets/standard_error.png)

**Limitation:** Independent synthetic exponential observations are a teaching model, not evidence that real-world time series satisfy these assumptions. More observations reduce standard error but do not automatically remove bias.

[View the project repository](https://github.com/OscarCarranzaFeynman/data-science-project) · [Read the analysis script](https://github.com/OscarCarranzaFeynman/data-science-project/blob/main/analysis.py)

**Project status:** Analysis completed locally; portfolio publication and genuine classmate feedback pending. Status will be updated only after verification.

## Next improvement

Ask a classmate to identify the research question, the main finding and the limitation, then make and commit one documented improvement based on their actual feedback.

## AI declaration

ChatGPT helped prepare and check this project and its explanation.
