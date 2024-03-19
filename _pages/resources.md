---
permalink: /resources/
title: "Resources"
author_profile: true
redirect_from:
  - /resources.html
---
Here are some resources that helped me tremendously (inspired by [Javier Donna](https://www.jdonna.org/resources))

# Job market candidates
* [List compiled by Shoshana Vasserman](https://shoshanavasserman.com/io-jmc/)

# Computation

* **Logit demand**
  * Kenneth Train's [codes on mixed logit](https://eml.berkeley.edu/~train/software.html)
  * Jason Blevin's post on [log sum of exponentials](https://jblevins.org/log/log-sum-exp) (what to do when my logit demand explodes?)
* **Dynamic discrete choice**
  * Victor Aguirregabiria's [compilation of codes on dynamic discrete choice](https://sites.google.com/view/victoraguirregabiriaswebsite/computer-code)
  * Jaap H. Abbring and Tobias J. Klein's [notes and codes on dynamic discrete choice](https://jabbring.github.io/dynamic-discrete-choice/dynamicDiscreteChoice.m.html)
* **Code optimization**
  * [Sparse grid for numerical integration](http://www.sparse-grids.de/)
  * Ken Judd's [Computational Economics course](https://kennethjudd.github.io/CompEcon2020/) on numerical methods
* **Code repositories for published papers**
  * [AEA journals (AER, AEJ)](https://www.openicpsr.org/openicpsr/aea)
  * [Econometrica](https://www.econometricsociety.org/publications/econometrica/journal-materials/supplemental-materials)
  * [ReStud](https://restud.github.io/data-editor/replicate/)
  * [Journal of Finance](https://voices.uchicago.edu/jfeditor/2018/03/06/code-sharing-policy-update/): scroll down on Wiley and click on supporting information
* **Others**
  * BU Research Computing Support's [guide on running batch jobs on a cluster](https://www.bu.edu/tech/support/research/system-usage/running-jobs/) and [parallel computing with MATLAB](https://www.bu.edu/tech/support/research/training-consulting/online-tutorials/matlab-pct/)
  * QuantEcon: a [Jupyter notebook library](https://notes.quantecon.org/) for economics and finance
  * [Matching data in financial databases](https://libguides.princeton.edu/MatchFinancial)

# Notes

* Chris Conlon's [Panel Data Econometrics](https://chrisconlon.github.io/metrics.html) and [IO](https://chrisconlon.github.io/gradio.html)
* Scott Cunningham's [Causal Inference: The Mixtape](https://mixtape.scunning.com/index.html)
* Jonathan Levin's [notes on market design and IO](https://web.stanford.edu/~jdlevin/teaching.html)
* Kohei Kawaguchi's [IO](https://kohei-kawaguchi.github.io/EmpiricalIO/)

# My go-to R packages

* Output LaTeX tables: ``stargazer``, ``texreg`` (supports ``fixest``), ``xtable``
* Fixed effects for linear models: ``plm`` (at most 2-way, need ``clubSandwich`` for clustering, good for 1 fixed effect with many unique values), ``lfe`` (clustering, fast)
* Fixed effects for non-linear models: ``fixest`` ([description](https://lrberge.github.io/fixest/)),  ``alpaca``
* Data wrangling: ``dplyr``, ``broom`` (turn regression results into a data frame), ``fastDummies``
