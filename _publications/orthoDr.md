---
title: "orthoDr: Semiparametric Dimension Reduction via Orthogonality Constrained Optimization"
collection: publications
permalink: /publication/orthoDr
date: 2019-07-01
venue: 'The R Journal'
citation: 'Ruoqing Zhu, Jiyang Zhang, Ruilin Zhao, <b>Peng Xu</b>, Wenzhuo Zhou, Xin Zhang. <i>The R Journal</i>. Jul 2017.'
---
[[PDF]](https://journal.r-project.org/archive/2019/RJ-2019-006/RJ-2019-006.pdf) [[R Package]](https://cran.r-project.org/web/packages/orthoDr/index.html)

## Abstract
orthoDr is a package in R that solves dimension reduction problems using orthogonality constrained optimization approach. The package serves as a unified framework for many regression and survival analysis dimension reduction models that utilize semiparametric estimating equations. The main computational machinery of orthoDr is a first-order algorithm developed by Wen and Yin (2012) for optimization within the Stiefel manifold. We implement the algorithm through Rcpp and OpenMP for fast computation. In addition, we developed a general-purpose solver for such constrained problems with user-specified objective functions, which works as a drop-in version of `optim()`. The package also serves as a platform for future methodology developments along this line of work.