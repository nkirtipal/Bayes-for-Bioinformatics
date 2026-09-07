# 01 — Bayes' Foundations

Bayes' theorem worked from first principles, using a biological example instead of coins or dice.

## Notebook

**`01_bayes_theorem_practical_introduction.ipynb`**

Question: *if a cell expresses CD3, how should we update our belief that it is a T cell?*

The notebook builds up to an answer piece by piece:

1. Prior probability — `P(T cell)`
2. Likelihood — `P(CD3 | T cell)`
3. Evidence — `P(CD3)`, via the law of total probability
4. Posterior — `P(T cell | CD3)`
5. Bayes' theorem, stated formally
6. A numerical example using 1,000 cells
7. A Python simulation confirming the theoretical result empirically
8. A bar chart visualizing the belief update
9. Changing the prior, showing how the same evidence leads to different posterior probabilities for common vs. rare cell types

The last section is especially useful: it shows why the same evidence can lead to very different posterior beliefs depending on how common the target cell type is.
