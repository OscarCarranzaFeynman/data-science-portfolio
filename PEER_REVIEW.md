# Peer feedback and improvement

Review date: 9 November 2026

Reviewer: A classmate; name and student ID omitted.

## Confirmed feedback

"The research question and charts are clear. I suggest adding a short explanation of how the simulation works, including how many samples were generated for each sample size. This would make the results easier to understand and reproduce."

The feedback wording was prepared with ChatGPT and confirmed by the classmate through Oscar.

## Change made

Added a "How the simulation works" section to the portfolio. It explains the exponential distribution, random seed 7204, sample sizes 5, 20 and 100, and 5,000 independent samples per size. It also explains how the script calculates empirical and theoretical standard errors and uses 100,000 separate values to illustrate the original distribution.

The analysis code and numerical results are unchanged. The explanation was checked against the published [analysis.py](https://github.com/OscarCarranzaFeynman/data-science-project/blob/main/analysis.py).

## Corresponding commit

[Explain simulation repetitions in response to classmate feedback](https://github.com/OscarCarranzaFeynman/data-science-portfolio/commit/3a3808a1fa8f1c9b502fa219533b51e9f856e0b9)

## AI declaration

ChatGPT helped prepare and check the wording and explanation.
