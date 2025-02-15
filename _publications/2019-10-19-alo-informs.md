---
title: "Approximate Leave-One-Out for Fast Parameter Tuning in High Dimensions"
collection: publications
category: conferences
permalink: /publication/alo_informs
date: 2019-10-19
venue: '<a href="https://sites.google.com/view/dmdaworkshop/">INFORMS Data Mining and Decision Analysis Workshop</a>'
citation: 'Wenda Zhou, Shuaiwen Wang, <b>Peng Xu</b>, Haiho Lu, Arian Maleki, Vahab Mirrokni. (2019). Approximate Leave-One-Out for Fast Parameter Tuning in High Dimensions. <i>2019 INFORMS Workshop on Data Mining and Decision Analytics</i>.'
---
[Link](http://francis-hsu.github.io/files/alo_informs.pdf){: .btn} [R Package](https://github.com/wendazhou/alocv-package){: .btn}

## Abstract
Consider the class of learning schemes which is composed of a sum of losses over every data point and a regularizer that imposes special structures on the model parameter and controls the model complexity. A tuning parameter, typically adjusting the amount of regularization, is necessary for this framework to work well. Finding the optimal tuning is a challenging problem in high-dimensional regimes where both the sample size and the dimension of the parameter space are large. We propose two frameworks to obtain a computationally efficient approximation of the leave-one-out cross validation (LOOCV) risk for nonsmooth losses and regularizers. Our two frameworks are based on the primal and dual formulations of the aforementioned learning scheme. We then prove the equivalence of the two approaches under smoothness conditions. This equivalence enables us to justify the accuracy of both methods under such conditions. Finally we apply our approaches to several standard problems, including generalized LASSO and support vector machines, and empirically demonstrate the effectiveness of our results.

## Award
[Best Theoretical Paper Finalists](https://connect.informs.org/data-mining/awards/new-item222758479866), INFORMS 2019 Data Mining and Decision Analytics Workshop Best Paper Competition Awards.