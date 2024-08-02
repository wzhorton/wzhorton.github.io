---
title: "Bayesian Nonparametric Curve Clustering"
date: 2020-06-01
type: docs
toc: false
backlinks: false
tags:
    - Paper
---

<div class = "custom-project-paragraph">
Functional data is really interesting, to me anyway. So similar to vector data, yet it exists in a very different space. I completed this project for a Bayesian nonparametrics course during my PhD. The contents are pretty technical, but it is a good example of the type of work I do in my research, i.e., connecting various statistical methods to solve a problem. I like this project specifically because it blends Bayesian nonparametrics, a primary theme in my PhD research, with functional data analysis, a central topic in my master's research.

To provide a more technical summary, this project has two purposes: to review a Bayesian nonparametric method called *density regression* and then combine it with a dependence structure to build a clustering model for functional curve data. Density regression is used to estimate nonlinear relationships between multiple variables, and it is specifically helpful in this project to model curve data. The dependence structure, called a *nested Dirichlet process*, is used to cluster force plate curves into groups. In the end, the model is capable of clustering functional curve data based on both shape and level, without the need to specify the number of clusters beforehand.
</div>
<br>
<embed src="/projects/bnp_curve_clustering.pdf" type="application/pdf" width="100%" height="900px" />
