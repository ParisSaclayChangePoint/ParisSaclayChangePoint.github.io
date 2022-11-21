---
layout: page
title: Speakers
permalink: /speakers/
---

### Farida Enikeeva

**Title:** Change-point detection in dynamic networks with missing links

**Abstract:** We consider the problem of change-point detection in a sequence of
partially observed networks. The goal is to detect whether there is a change in the network
parameters. Our approach is based on the Matrix CUSUM test statistic and allows growing
size of networks. We show that the proposed test is minimax rate-optimal and robust to missing links.

This is a joint work with Olga Klopp. 

[Link to article](https://arxiv.org/pdf/2106.14470.pdf)

***

### Shakeel Gavioli-Akilagun

**Title:** Uncovering Causality in Change Point Regressions

We propose a method for estimating graphs which encode (non-) causality between change points present in a moderate number of data streams. Typically after performing change point analysis relationships between estimated change points can only be described qualitatively, since in general change point locations are held to be unknown but non-stochastic. From the perspective of prac- titioners this is a limitation, since in many settings it is reasonable to believe change points will be causally linked. For example: in climatology changes in concentrations levels of certain gasses actively cause changes in the environment [1]. We model unobserved change point locations as arrival times of a marked point process, for which non-causality is well understood [2]. Estimated change point locations can therefore be seen as a noisy sample path of the same process, to which existing estimation procedures can be applied. We will give details of this ongoing work, and provide real data examples illustrating its practical value.

This is a joint work with Piotr Fryzlewicz. 

[1] Andreas Schmittner (2018), Introduction to Climate Science, Oregon State University
<br>
[2] Vanessa Didelez, Graphical models for marked point processes based on local independence, Journal of the Royal Statistical Society: Series B (Statistical Methodology)

***

### Rebecca Killick

**Title:** Detecting changes in mixed-sampling rate data sequences

**Abstract:** Different environmental variables are often monitored using different sampling rates; examples include half-hourly weather station measurements, daily CO<sub>2</sub> data and six-day satellite data. When researchers want to combine the data into a single analysis this often requires data aggregation or down-scaling. Further, when one is seeking to identify changes within multivariate data, the aggregation and/or down-scaling processes obscure the changes we seek. In this talk, we propose a novel changepoint detection algorithm which can analyse multiple time series for co-occurring changepoints with potentially different sampling rates, without requiring preprocessing to a standard sampling scale. We demonstrate the algorithm on synthetic data before providing an example identifying simultaneous changes in multiple variables at a location on the Greenland ice sheet using synthetic apature radar (SAR) and weather station data.

***

### Émilie Lebarbier

**Title:** Multiple change-point detection in a Poisson process 

**Abstract:** We consider a Poisson process whose intensity is supposed to be piecewise constant. The objective is to detect the instants of abrupt changes, called change-point, and to determine their number.
<br>
The main difficulty concerns the estimation of the change-points. Indeed, the based-likelihood contrast to be optimized for this purpose is not convex and nor even continous with respect to these parameters. This problem has been already considered in the literature for the detection of one change-point [1,2]. Using a concavity argument of the contrast on each time-event intervals, they showed that the optimal change-point is necessarly localized at an event or just before. For the detection of multiple change-points, we use the same idea and show that, for a general class of contrasts satisfying a concavity hypothesis w.r.t. the change-points, the optimization problem is thus reduced to a discrete optimization problem which can be solved using a well-efficient algorithm known used in the case of the detection of discrete change-points, the dynamic programming algorithm. The change-points are thus recovered in a exact manner and reasonnably fast.
<br>
For the choice of the number of change-points, we propose to use a cross-validation method taking advantage of the previous fast algorithm and a specific property of Poisson processes.
<br>
Simulation results will be presented as well as an illustration of volcanic eruption data.

This is joint work with Charlotte Dion and Stéphane Robin.

[1] Qing Li, Recurrent-event models for change-points detection, Ph.D. thesis, Virginia Tech, 2015.
<br>
[2] Tae Young Yang and Lynn Kuo, Bayesian binary segmentation procedure for a poisson process with multiple changepoints, Journal of Computational and Graphical Statistics 10 (2001), no. 4, 772–785.


***
### Igor Nikiforov

**Title:** Sequential detection of abrupt changes: some criteria and methods
 
**Abstract:** The goal of this presentation is to discuss the relation between the criteria of optimality in sequential detection of abrupt changes and the methods used to get the desired operating characteristics. The presentation is divided in three parts. The first part is devoted to the quickest detection of abrupt changes when the post-change hypothesis is simple or composite. The criterion is to minimize the (worst-case) mean detection delay for a given ARL to false alarm. Here we discuss how the a priori information on the post-change distribution affects the structure and operating characteristics of the sequential tests. We also discuss how the nuisance parameters in the pre- and post-change stochastic models affect the sequential tests. The second part is devoted to the quickest multidecision change detection/isolation problem, which is the generalization of the quickest changepoint detection problem to the case of M>1 post-change hypotheses. The criterion is to minimize the (worst-case) mean detection delay for a given ARL to false alarm and for a given probability of false isolation. A special attention will be paid to the case of M non-orthogonal post-change hypotheses. The comparison between the sequential and non-sequential or fixed sample size (FSS) tests will be also considered here for the cases of M=1 and M>1 post-change hypotheses. Finally, the third part is devoted to the reliable detection of transient changes, i.e., it is assumed that the duration of the post-change period is finite and usually short. Unlike the quickest sequential change detection, which assumes that the post-change period is infinitely long, we use here the probabilistic criterion of optimality, i.e., the worst-case probability of missed detection against the worst-case probability of false alarm during a reference period. We discuss the optimization of the window-limited CUSUM test and its comparison with the FSS test. Several typical real-life examples will be given to illustrate the theoretical ideas.

***

### Florian Pein

**Title:** High-dimensional change-point regression with structured information

**Abstract:** Observing a large number of time series of related processes at the same time occurs in more and more applications. Consequently, recently many works have considered the detection of change-points that occur in multiple of the time series simultaneously. Sharing the information of the change-point location among different time series increases detection power heavily. In this talk we will consider the situation where we additionally know that all changes have the same sign, i.e. all changes at a certain location are either upwards or downwards. We will propose methodology that have a larger detection power if this situation is given. We will discuss application where this setting occurs, show the increase of detection power in a minimax theory and in numerical simulations.

This is joint work with Hyeyoung Maeng, Paul Fearnhead and Idris Eckley.

***

### Gaetano Romano

**Title:** Ex-FOCuS: A Constant-per-Iteration Likelihood Ratio Test for Online Changepoint Detection for Exponential Family Models

**Abstract:** Online changepoint detection algorithms that are based on likelihood-ratio tests have been shown to have excellent statistical properties. However, a simple online implementation is computationally infeasible as, at time *T*, it involves considering *O(T)* possible locations for the change. Recently, the FOCuS algorithm has been introduced for detecting changes in mean in Gaussian data that decreases the per-iteration cost to *O(log(T))*. This is possible by using pruning ideas, which reduce the set of changepoint locations that need to be considered at time *T* to approximately *log(T)*. We show that if one wishes to perform the likelihood ratio test for a different one-parameter exponential family model, then exactly the same pruning rule can be used, and again one need only consider approximately *log(T)* locations at iteration *T*. Furthermore, we show how we can adaptively perform the maximisation step of the algorithm so that we need only maximise the test statistic over a small subset of these possible locations. Empirical results show that the resulting online algorithm, which can detect changes under a wide range of models, has a constant-per-iteration cost on average.

***

### Nicolas Verzelen

**Title:** Optimal change-point detection and localization

**Abstract:** Given a times series, we consider the twin problems of detecting and localizing change-points in the distribution. This encompasses various models including mean univariate, sparse multivariate, non-parametric, or kernel change-points... Starting with the simple Gaussian univariate model, we derive optimal detection and localization rates and uncover phase transitions from regional testing problems to local estimation problems. Notably, our multi-scale procedures accommodate with the presence of possibly many low-energy and therefore undetectable change-points. In a second part, we explain how the methodology extends to more generic change-point problems by drawing some connection with minimax theory in multiple testing. This is based on joint works with A. Carpentier, M. Fromont, M. Lerasle, E. Pilliat, and P. Reynaud-Bouret. 

[Link to article](https://arxiv.org/pdf/2010.11470.pdf)

***

### Martin Wendler

**Title:** Detection of Epidemic Changes Based on Weighted U-Statistics

To detect a changed segment (a so called epidemic changes) in a time series, variants of the CUSUM statistic are frequently used. However, they are sensitive to outliers in the data and do not perform well for heavy tailed data, especially when short segments are given high weights in the test statistic. We will present a robust test statistic for epidemic changes based on a weighted version of the Wilcoxon rank statistic. To study their asymptotic behavior, we prove functional limit theorems for general U-processes in Hölder spaces. We assume that the time series is short range dependent in the sense of absolute regularity. Under the alternative, we show that the test is consistent. We also study the finite sample behavior via simulations and apply the statistics to a real data example.

This is a joint work with Alfredas Račkauskas

[Link to article](https://doi.org/10.1007/s00362-020-01161-9)