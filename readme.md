# Nonparametric Inference, Auditing, and Litigation
## Short course at [XXIX International Forum on Statistics](http://www.upaep.mx/micrositios/29foroestadistica/)
## Puebla, Mexico, 29 September&ndash;3 October 2014
### [Philip B. Stark](www.stat.berkeley.edu/~stark)
### [Department of Statistics](statistics.berkeley.edu), [University of California, Berkeley](www.berkeley.edu)

### These materials are available at https://github.com/pbstark/MX14

*Abstract:* Many problems that arise in auditing, civil litigation,
and causal inference can be reduced to statistical inferences about
the mean of a nonnegative or bounded finite population.
Examples include election auditing, financial auditing, tax auditing,
healthcare auditing, intellectual property litigation, wage and hour
litigation, and online advertising. A variety of sampling plans can be
combined with common probability inequalities to test hypotheses or make
confidence intervals in these applications, in a fully nonparametric,
conservative way. We will derive a handful of such methods using tools
such as binomial and hypergeometric tests, Markov's inequality,
Chebychev's inequality, Hoeffding's inequality, and the DKW inequality.
An especially useful class of methods can be derived from Wald's (1945)
sequential probability ratio test (SPRT), which hinges on a generalization
of the problem of gambler's ruin.
Methods based on Wald's SPRT allow samples to be drawn incrementally and
adaptively, often reducing the cost of financial and electoral audits,
litigation discovery,
and experiments, without incurring any penalty from multiple testing.
We will compare the performance of these methods in simulations from
"nonstandard" mixtures of distributions.

## Description of the materials

This course comprises a series of IPython notebooks.

To view them, you can either clone this github repository onto your own machine
(which would then let you change parameters,
modify the scripts, etc.) or navigate to
http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/ to see a statically rendered version.

The chapters are:

1. [Canonical examples of real-world problems we will consider](canonical.ipynb)
1. [Why not use the normal approximation?](normApprox.ipynb)
1. [The duality between confidence sets and hypothesis tests](duality.ipynb)
1. [Confidence bounds for the mean of a bounded population: Binomial and Hypergeometric](binom.ipynb)
1. [Confidence bounds from the Chebychev and Hoeffding Inequalities](hoeffding.ipynb)
1. [Lower confidence bounds for the mean of a nonnegative population: Markov's Inequality & methods based on the empirical distribution](markov.ipynb)
1. [Wald's Sequential Probability Ratio Test](sprt.ipynb)
1. [The Kaplan-Wald Confidence Bound for a Nonnegative Mean](kaplanWald.ipynb)
1. [Dollar-unit sampling and taint](dus.ipynb)
1. [Penny Sampling and Continuous Penny Sampling](pennySampling.ipynb)
1. [Method shootout](shootout.ipynb)
1. [Bibliography](bib.ipynb)

If you discover errors or bugs, please let me know.

If you find these materials useful, please let me know.