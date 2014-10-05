# Nonparametric Inference, Auditing, and Litigation
## Short course at [XXIX International Forum on Statistics](http://www.upaep.mx/micrositios/29foroestadistica/)
## Puebla, Mexico, 29 September&ndash;3 October 2014
### [Philip B. Stark](www.stat.berkeley.edu/~stark)
### [Department of Statistics](statistics.berkeley.edu), [University of California, Berkeley](www.berkeley.edu)

### These materials are available at https://github.com/pbstark/MX14

*Abstract:* Many problems that arise in financial and election auditing,
civil litigation,
and causal inference can be reduced to statistical inferences about
the mean of a nonnegative or bounded finite population.
A variety of sampling plans can be combined with common probability
inequalities to test hypotheses or make confidence intervals in these applications,
in a fully nonparametric, conservative way.
I will illustrate these methods with real and cartoon examples from election auditing,
healthcare auditing, intellectual property litigation, wage and hour litigation,
and online advertising.
An especially useful class of methods can be derived from Wald's (1945)
sequential probability ratio test (SPRT), which hinges on a generalization of the
problem of _gambler's ruin_.
Methods based on Wald's SPRT allow samples to be drawn incrementally and adaptively,
often reducing the cost of financial and electoral audits, litigation discovery,
and experiments without incurring any penalty from multiple testing.

## Description of the materials

This course comprises a series of IPython notebooks.

To view them, you can either clone this github repository onto your own machine
(which would then let you change parameters,
modify the scripts, etc.) or navigate to
http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/ to see a statically rendered version.

The chapters are:

1. [Canonical examples of real-world problems we will consider](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/canonical.ipynb)
1. [Why not use the normal approximation?](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/normApprox.ipynb)
1. [The duality between confidence sets and hypothesis tests](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/duality.ipynb)
1. [Confidence bounds for the mean of a bounded population: Binomial and Hypergeometric](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/binom.ipynb)
1. [Confidence bounds from the Chebychev and Hoeffding Inequalities](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/hoeffding.ipynb)
1. [Lower confidence bounds for the mean of a nonnegative population: Markov's Inequality & methods based on the empirical distribution](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/markov.ipynb)
1. [Dollar-unit sampling and taint](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/dus.ipynb)
1. [Penny sampling](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/pennySampling.ipynb)
1. [Wald's Sequential Probability Ratio Test](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/sprt.ipynb)
1. [The Kaplan-Wald Confidence Bound for a Nonnegative Mean](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/kaplanWald.ipynb)
1. [Stratification and its discontents](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/stratify.ipynb)
1. [Applications to auditing and litigation](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/applications.ipynb)
1. [Bibliography](http://nbviewer.ipython.org/github/pbstark/MX14/tree/master/bib.ipynb)

As of 30 September 2014, only the first five chapters are complete,
but I hope to finish the rest within a few days.

If you discover errors or bugs, please let me know.

If you find these materials useful, please let me know.