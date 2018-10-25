<a href="http://mc-stan.org">
<img src="https://raw.githubusercontent.com/stan-dev/logos/master/logo.png" width=150 alt="Stan Logo"/>
</a>

# Materials from StanCon

StanCon’s version of conference proceedings is a collection of contributed talks based on interactive notebooks. Every submission is peer reviewed by at least two reviewers. The reviewers are members of the Stan Conference Organizing Committee and the Stan Developmemt Team. This repository contains all of the accepted notebooks as well as any supplementary materials required for building the notebooks. The slides presented at the conference are also included.

**License**: unless otherwise noted, the text in this repository is distributed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode) and code is distributed under the [New BSD License](https://opensource.org/licenses/BSD-3-Clause). Copyright to the authors.

### Contents:

**2017 NYC**

* [Contributed talks](#2017-peer-reviewed-contributed-talks) 

**2018 Asilomar**

* [Contributed talks](#2018-peer-reviewed-contributed-talks)
* [Invited talks](#2018-invited-talks) 

**2018 Helsinki**

* [Contributed talks](#2018-helsinki-peer-reviewed-contributed-talks)
* [Invited talks](#2018-helsinki-invited-talks) 


<br>

## StanCon 2017 | January 21, Columbia University, New York

### 2017 Peer reviewed contributed talks

**_Twelve Cities: Does lowering speed limits save pedestrian lives?_**      

* Authors: Jonathan Auerbach, Rob Trangucci (Columbia University)

We investigate whether American cities can expect to achieve a meaningful reduction in pedestrian deaths by lowering the posted speed limit. We find some evidence that a lower speed limit does in fact reduce fatality rates, and our estimated causal effect is similar to the traditional before-after analysis espoused by policy analysts. Nevertheless, we conclude that adjusting the posted speed limit in urban environments does not correspond with a reliable reduction in pedestrian fatalities.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1283490.svg)](https://doi.org/10.5281/zenodo.1283490)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=1h58m49s)
  - [Notebook and materials](2017/Contributed-Talks/01_auerbach)
  - [Slides](2017/Contributed-Talks/slides/01_auerbach_stancon_slides.pdf)
  - https://github.com/jauerbach


<br> 

**_Hierarchical Bayesian Modeling of the English Premier League_**    

* Authors: Milad Kharratzadeh (Columbia University)

In this case study, we provide a hierarchical Bayesian model for the English Premier League in the season of 2015/2016. The league consists of 20 teams and each two teams play two games with each other (home and away games). So, in total, there are 38 weeks, and 380 games. We model the score difference (home team goals − away team goals) in each match. The main parameters of the model are the teams’ abilities which is assumed to vary over the course of the 38 weeks. The initial abilities are determined by performance in the previous season plus some variation.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1283496.svg)](https://doi.org/10.5281/zenodo.1283496)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=2h12m12s)
  - [Notebook and materials](2017/Contributed-Talks/02_kharratzadeh); 
  - [Slides](2017/Contributed-Talks/slides/02_kharratzadeh_stancon_slides.pdf)
  - http://www.columbia.edu/~mk3971/


<br>

**_Advertising Attribution Modeling in the Movie Industry_** 

* Authors: Victor Lei, Nathan Sanders, Abigail Dawson (Legendary Entertainment)

We present a Bayesian method for inferring advertising platform effectiveness as applied to the movie industry, and show some possibilities for drawing inferences by analyzing model parameters at different levels of the hierarchy. In addition, we show some common ways to check model efficacy, and possibilities for comparing between different models.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284248.svg)](https://doi.org/10.5281/zenodo.1284248)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=2h25m43s)
  - [Notebook and materials](2017/Contributed-Talks/03_lei)
  - [Slides](2017/Contributed-Talks/slides/03_lei_stancon_slides.pdf)
  - https://github.com/foo-bar-baz-qux


<br>

**_hBayesDM: Hierarchical Bayesian modeling of decision-making tasks_** 

* Authors: Woo-Young Ahn, Nate Haines, Lei Zhang (Ohio State University)

hBayesDM (hierarchical Bayesian modeling of Decision-Making tasks) is a user-friendly R package that offers hierarchical Bayesian analysis of various computational models on an array of decision-making tasks. 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284262.svg)](https://doi.org/10.5281/zenodo.1284262)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=2h40m20s)
  - [Notebook and materials](2017/Contributed-Talks/04_ahn)
  - [Slides](2017/Contributed-Talks/slides/04_ahn_stancon_slides.pdf)
  - https://ccs-lab.github.io


<br>

**_Differential Equation Based Models in Stan_** 

* Authors: Charles Margossian, Bill Gillespie (Metrum Research Group)

Differential equations can help us model sophisticated processes in biology, physics, and many other fields. Over the past year, the Stan team has developed many tools to tackle models based on differential equations.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284264.svg)](https://doi.org/10.5281/zenodo.1284264)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=2h53m26s)
  - [Notebook and materials](2017/Contributed-Talks/05_margossian)
  - [Slides](2017/Contributed-Talks/slides/05_margossian_stancon_slides.pdf)
  - http://metrumrg.com/


<br>

**_How to Test IRT Models Using Simulated Data_**

* Authors: Teddy Groves (Football Radar)

This notebook explains how to code some IRT models using Stan and test whether they can recover input parameters when given simulated data.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284275.svg)](https://doi.org/10.5281/zenodo.1284275)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=6h3m16s)
  - [Notebook and materials](2017/Contributed-Talks/06_groves)
  - [Slides](2017/Contributed-Talks/slides/06_groves_stancon_slides.html)
  - https://kent.academia.edu/TeddyGroves


<br>

**_Models of Retrieval in Sentence Comprehension_** 

* Authors: Bruno Nicenboim, Shravan Vasishth (University of Potsdam)

This work presents an evaluation of two well-known models of retrieval processes in sentence comprehension, the activation-based model and the direct-access model. We implemented these models in a Bayesian hierarchical framework and showed that some aspects of the data can be explained better by the direct access model. Specifically, the activation-based cannot predict that, on average, incorrect retrievals would be faster than correct ones. More generally, our work leverages the capabilities of Stan to provide a powerful framework for flexibly developing computational models of competing theories of retrieval, and demonstrates how these models’ predictions can be compared in a Bayesian setting.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284286.svg)](https://doi.org/10.5281/zenodo.1284286)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=6h18m1s)
  - [Notebook and materials](2017/Contributed-Talks/07_nicenboim) 
  - [Slides](2017/Contributed-Talks/slides/07_nicenboim_stancon_slides.pdf)
  - http://www.ling.uni-potsdam.de/~nicenboim/
  

<br>

**_Hierarchical Gaussian Processes in Stan_** 

* Authors: Rob Trangucci (Columbia University)

Stan’s library has been expanded with functions that facilitate adding Gaussian processes (GPs) to Stan models. I will share the best practices for coding GPs in Stan, and demonstrate how GPs can be added as one component of a larger model.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284293.svg)](https://doi.org/10.5281/zenodo.1284293)

Links: 

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=6h31m27s)
  - [Notebook and materials](2017/Contributed-Talks/08_trangucci)
  - [Slides](2017/Contributed-Talks/slides/08_trangucci_stancon_slides.pdf)
  - https://github.com/rtrangucci
  

<br>

**_Modeling the Rate of Public Mass Shootings with Gaussian Processes_** 

* Authors: Nathan Sanders, Victor Lei (Legendary Entertainment)

We have used Stan to develop a new model for the annualized rate of public mass shootings in the United States based on a Gaussian process with a time-varying mean function. This design yields a predictive model with the full non-parametric flexibility of a Gaussian process, while retaining the direct interpretability of a parametric model for long-term evolution of the mass shooting rate. We apply this model to the Mother Jones database of public mass shootings and explore the posterior consequences of different prior choices and of correlations between hyperparameters. We reach conclusions about the long term evolution of the rate of public mass shootings in the United States and short-term periods deviating from this trend.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284299.svg)](https://doi.org/10.5281/zenodo.1284299)

Links:

  - [Video](https://youtu.be/DJ0c7Bm5Djk?t=6h45m55s)  
  - [Notebook and materials](2017/Contributed-Talks/09_sanders)
  - [Slides](2017/Contributed-Talks/slides/09_sanders_stancon_slides.pdf)
  - https://github.com/nesanders



<br>

  
## StanCon 2018 | January 10-12, Asilomar, California  

### 2018 Peer reviewed contributed talks

**_Does the New York City Police Department rely on quotas?_** 

* Authors: Jonathan Auerbach (Columbia University)

This submission investigates whether the New York City Police Department (NYPD) uses productivity targets or quotas to manage officers in contravention of New York State Law. The analysis is presented in three parts. First, the NYPD's employee evaluation system is introduced, and the criticism that it constitutes a quota is summarized. Secondly, a publically available dataset of traffic tickets issued by NYPD officers in 2014 and 2015 is described. Finally, a generative model to describe how officers write traffic tickets is proposed. The fitted model is consistent with the criticism that police officers substantially alter their ticket writing to coincide with departmental targets. The submission concludes by discussing the implication of these findings and offering directions for further research.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284317.svg)](https://doi.org/10.5281/zenodo.1284317)

Links: 

  - [Video](https://youtu.be/5qojKAiirqI)
  - [Notebook, code, slides](2018/Contributed-Talks/01_auerbach) 
  - <a href="https://github.com/jauerbach"> github.com/jauerbach</a>

  
<br>  

**_Diagnosing Alzheimer’s the Bayesian way_** 

* Authors: Arya A. Pourzanjani, Benjamin B. Bales, Linda R. Petzold, Michael Harrington (UC Santa Barbara)

Alzheimer's Disease is one the most debilitating diseases, but how do we diagnose it accurately? Researchers have been trying to answer this question by building generative models to describe how patient biomarkers, such as MRI scans, psychological tests, and lab tests relate over time to the underlying brain deterioration that's present in Alzheimer's Disease. In this notebook we show how we translated these models to the Bayesian framework in Stan and how this allowed for several model improvements that can ultimately improve our understanding of Alzheimer's and help physicians in diagnosis. In particular, we describe how we hierarchically model patient disease trajectories to obtain stable estimates for patients who lack data. We describe how fitting in Stan yields uncertainties on these disease trajectories, and why that is important for weighing the pros and cons of risky treatment. Lastly, we describe a new method for Bayesian modeling of these monotonic disease trajectories in Stan using I-Splines.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284330.svg)](https://doi.org/10.5281/zenodo.1284330)

Links: 

  - [Video](https://youtu.be/j_JIfNiO9TA)
  - [Notebook, code, slides](2018/Contributed-Talks/02_pourzanjani)
  - [https://github.com/pourzanj/Stancon2018\_Alzheimers](https://github.com/pourzanj/Stancon2018_Alzheimers)
  - <a href="https://aryastats.com/"> aryastats.com</a>

<br>  

**_Joint longitudinal and time-to-event models via Stan_** 

* Authors: Sam Brilleman, Michael Crowther, Margarita Moreno-Betancur, Jacqueline Buros Novik, Rory Wolfe (Monash University, Columbia University)

The joint modelling of longitudinal and time-to-event data has received much attention in the biostatistical literature in recent years. In this notebook (and talk), we describe the implementation of a shared parameter joint model for longitudinal and time-to-event data in Stan. The methods described in the
notebook are a simplified version of those underpinning the `stan_jm` modeling function that has recently been contributed to the [**rstanarm**](http://mc-stan.org/rstanarm) R package.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284334.svg)](https://doi.org/10.5281/zenodo.1284334)

Links: 

  - [Video](https://youtu.be/8r-Ipt885FA)
  - [Notebook, code, slides](2018/Contributed-Talks/03_brilleman) 
  - [github.com/sambrilleman/2018-StanCon-Notebook](https://github.com/sambrilleman/2018-StanCon-Notebook)
  - <a href="http://www.sambrilleman.com/"> sambrilleman.com</a>


<br>

**_A tutorial on Hidden Markov Models using Stan_** 

* Authors: Luis Damiano, Brian Peterson, Michael Weylandt 

We implement a standard Hidden Markov Model (HMM) and the Input-Output Hidden Markov Model for unsupervised learning of time series dynamics in Stan. We begin by reviewing three commonly-used algorithms for inference and parameter estimation, as well as a number of computational techniques and modeling strategies that make full Bayesian inference practical. For both models, we demonstrate the effectiveness of our proposed approach in simulations. Finally, we give an example of embedding a HMM within a larger model using an example from the econometrics literature.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284341.svg)](https://doi.org/10.5281/zenodo.1284341)

Links: 

  - [Video](https://youtu.be/oe9PAEI97oI)
  - [Notebook, code, slides](2018/Contributed-Talks/04_damiano) 
  - <a href="https://github.com/luisdamiano/stancon18"> github.com/luisdamiano/stancon18</a>

  
<br>

**_Student Ornstein-Uhlenbeck models served three ways (with applications for population dynamics data)_** 

* Authors: Aaron Goodman (Stanford University)

Ornstein-Uhlenbeck (OU) processes are a mean reverting process and is used to model dynamics in biology, physics, and finance. I fit an extension of the OU process that is driven by a Lévy process with Student's t-marginals rather than Brownian motion with Gaussian marginals, which allows for heavy-tailed increments. I implement four formulations of the Student-t OU-type model in Stan and compare the sampling performance on both real and simulated population dynamic data. 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284346.svg)](https://doi.org/10.5281/zenodo.1284346)

Links: 

  - Video (coming soon)
  - [Notebook, code, slides](2018/Contributed-Talks/05_goodman) 
  - [github.com/aaronjg/outype\_t\_process\_stan](https://github.com/aaronjg/outype_t_process_stan)
  - <a href="https://web.stanford.edu/~aaronjg/"> web.stanford.edu/~aaronjg</a>

  
<br>  

**_SlicStan: a blockless Stan-like language_** 

* Authors: Maria I. Gorinova, Andrew D. Gordon, Charles Sutton (University of Edinburgh) 

We present SlicStan — a probabilistic programming language that compiles to Stan and uses static analysis techniques to allow for more abstract and flexible models. SlicStan is novel in two ways: (1) it allows variable declarations and statements to be automatically shredded into different components needed for efficient Hamiltonian Monte Carlo inference, and (2) it introduces more flexible user-defined functions that allow for new model parameters to be declared as local variables. This work demonstrates that efficient automatic inference can be the result of the machine learning and programming languages communities joint efforts.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284348.svg)](https://doi.org/10.5281/zenodo.1284348)

Links: 

  - [Video](https://youtu.be/WTqnehdFNbo)
  - [Notebook, code, slides](2018/Contributed-Talks/06_gorinova) 
  - [github.com/mgorinova/SlicStan-Paper](https://github.com/mgorinova/SlicStan-Paper)
  - <a href="http://homepages.inf.ed.ac.uk/s1207807/"> homepages.inf.ed.ac.uk/s1207807</a>, <a href="https://www.microsoft.com/en-us/research/people/adg/"> microsoft.com/en-us/research/people/adg</a>, <a href="http://homepages.inf.ed.ac.uk/csutton/"> http://homepages.inf.ed.ac.uk/csutton</a> 


<br>

**_idealstan: an R package for ideal point modeling with Stan_** 

* Authors: Robert Kubinec (University of Virginia)

Item-response theory (IRT) ideal-point scaling/dimension reduction methods that incorporate additional response categories and missing/censored values, including absences and abstentions, for roll call voting data (or any other kind of binary or ordinal item-response theory data). Full and approximate Bayesian inference is done via Stan.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284361.svg)](https://doi.org/10.5281/zenodo.1284361)

Links: 

  - [Video](https://youtu.be/0ZjrLOosXwk)
  - [Notebook, code, slides](2018/Contributed-Talks/07_kubinec) 
  - [https://CRAN.R-project.org/package=idealstan](https://CRAN.R-project.org/package=idealstan)


<br>  

**_Computing steady states with Stan’s nonlinear algebraic solver_** 

* Authors: Charles C. Margossian (Metrum, Columbia University)

Stan’s numerical algebraic solver can be used to solve systems of nonlinear algebraic equations with no closed form solutions. One of its key applications in scientific and engineering fields is the computation of equilibrium states (equivalently steady states). This case study illustrates the use of the algebraic solver by applying it to a problem in pharmacometrics. In particular, I show the algebraic system we solve can be quite complex and embed, for instance, numerical solutions to ordinary differential equations. The code in R and Stan are provided, and a Bayesian model is fitted to simulated data. 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1284375.svg)](https://doi.org/10.5281/zenodo.1284375)

Links: 

  - [Video](https://youtu.be/JhwZIX5ryw0) 
  - [Notebook, code, slides](2018/Contributed-Talks/08_margossian) 
  - [github.com/charlesm93](https://github.com/charlesm93)


<br>

**_Bayesian estimation of mechanical elastic constants_** 

* Authors: Ben Bales, Brent Goodlet, Tresa Pollock, Linda Petzold (UC Santa Barbara)

This outlines a Bayesian approach to resonance ultrasound spectroscopy (RUS), a technique for estimating elastic constants of a material from a sample's measured resonance modes. The notebook includes an example of how to take advantage of custom automatic differentiation in specialized Stan models (either for numerical or efficiency reasons).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1285265.svg)](https://doi.org/10.5281/zenodo.1285265)

Links: 

  - [Video](https://youtu.be/vOoZBTpN8n4)
  - [Notebook, code, slides](2018/Contributed-Talks/09_bales) 
  - [github.com/bbbales2/stancon_2018](https://github.com/bbbales2/stancon_2018)


<br>

**_Aggregate random coefficients logit — a generative approach_** 

* Authors: Jim Savage (Lendable Marketplace), Shoshana Vasserman (Harvard University).

This notebook illustrates how to fit aggregate random coefficient logit models in Stan, using Bayesian techniques. It’s far easier to learn and implement than the standard BLP algorithm, and has the benefits of being robust to mismeasurement of market shares, and giving limited-sample posterior uncertainty of all parameters (and demand shocks). This comes at the cost of modeling firms’ price-setting process, including how unobserved product-market demand shocks affect prices.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1285268.svg)](https://doi.org/10.5281/zenodo.1285268)

Links: 

  - [Video](https://youtu.be/LDOhRIRRe8M)
  - [Notebook, code, slides](2018/Contributed-Talks/10_savage) 
  - [github.com/khakieconomics](https://github.com/khakieconomics), [github.com/shoshievass](https://github.com/shoshievass)


<br>

**_The threshold test: Testing for racial bias in vehicle searches by police_** 

* Authors: Camelia Simoiu, Sam Corbett-Davies, Sharad Goel, Emma Pierson (Stanford University)

We develop a new statistical test to detect bias in decision making — the threshold test—that mitigates the problem of infra-marginality by jointly estimating decision thresholds and risk distributions.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1285270.svg)](https://doi.org/10.5281/zenodo.1285270)

Links: 

  - [Video](https://youtu.be/vEO-rjAqGW8)
  - [Notebook, code, slides](2018/Contributed-Talks/11_simoiu) 
  - [github.com/camioux/stancon2018](https://github.com/camioux/stancon2018) 
  - [web.stanford.edu/~csimoiu](http://web.stanford.edu/~csimoiu/), [samcorbettdavies.com](https://samcorbettdavies.com/), [cs.stanford.edu/~emmap1](https://cs.stanford.edu/~emmap1/), [5harad.com](https://5harad.com/)


<br>

**_Assessing the safety of Rosiglitazone for the treatment of type II diabetes_** 

* Authors: Konstantinos Vamvourellis, K. Kalogeropoulos, L. Phillips (London School of Economics and Political Science) 

A Bayesian paradigm for making drug approval decisions. Case study in the treatment of Diabetes (Type 2).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1285274.svg)](https://doi.org/10.5281/zenodo.1285274)

Links: 

  - [Video](https://youtu.be/Gt73VNaZLXA)
  - [Notebook, code, slides](2018/Contributed-Talks/12_vamvourellis) 
  - [github.com/bayesways/case\_studies\_R/tree/master/stancon18](https://github.com/bayesways/case_studies_R/tree/master/stancon18)
  - [personal.lse.ac.uk/vamourel/](http://personal.lse.ac.uk/vamourel/)


<br>

**_Causal inference with the g-formula in Stan_** 

* Authors: Leah Comment (Harvard University)

The potential outcomes framework often uses one or more parametric outcome models to learn about underlying causal processes. In Stan, parameter estimation using observed data takes place in the model block, while simulation-based estimation of causal parameters using the g-formula can be done separately with generated quantities. Bayesian estimation allows for data-driven sensitivity analysis regarding the assumption of no unmeasured confounding. This presentation shows some simple causal models, then outlines a basic sensitivity analysis using prior information derived from an external data source.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1285276.svg)](https://doi.org/10.5281/zenodo.1285276)

Links: 

  - [Video](https://youtu.be/W3gnbG0v4IE)
  - [Notebook, code, slides](2018/Contributed-Talks/13_comment) 
  - [https://github.com/lcomm/stancon2018](https://github.com/lcomm/stancon2018)
  - [scholar.harvard.edu/leahcomment](https://scholar.harvard.edu/leahcomment/)

<br>

**_Bayesian estimation of ETAS models with Rstan_** 

* Authors: Fausto Fabian Crespo Fernandez (Universidad San Francisco de Quito)

Earthquake modeling with Stan. Applied to seismic recurrence in Ecuador in 2016.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1285278.svg)](https://doi.org/10.5281/zenodo.1285278)

Links: 

  - [Video](https://youtu.be/hTswMCRzltQ)
  - [Notebook, code, slides](2018/Contributed-Talks/14_crespo) 
  - [linkedin.com/in/phd-student-fausto-fabian-crespo-fernandez](https://www.linkedin.com/in/phd-student-fausto-fabian-crespo-fernandez-2b457a71/)


<br>

### 2018 Invited talks 

**_Predictive information criteria in hierarchical Bayesian models for clustered data_**
    
* Presenters: Sophia Rabe-Hesketh, Daniel Furr (UC Berkeley)
* [Video](https://youtu.be/FiSw6adfZcY)
* [Slides and code](2018/Invited-Talks/RabeHesketh_Furr) 
* [gse.berkeley.edu/people/sophia-rabe-hesketh](https://gse.berkeley.edu/people/sophia-rabe-hesketh), [github.com/danielcfurr](https://github.com/danielcfurr)

**_ScalaStan_** 

* Presenter: Joe Wingbermuehle (Cibo Technologies)
* [Video](https://youtu.be/OtggQJI4J7U)
* [Slides](2018/Invited-Talks/Wingbermuehle.pdf) 
* <a href="https://github.com/cibotech/ScalaStan"> github.com/cibotech/ScalaStan</a>

**_Stan applications in physics: Testing quantum mechanics and modeling neutrino masses_**

* Presenter: Talia Weiss (MIT)
* [Slides](2018/Invited-Talks/Weiss.pdf) 
* [https://www.linkedin.com/in/talia-weiss-184753139](https://www.linkedin.com/in/talia-weiss-184753139/)


**_Forecasting at scale: How and why we developed Prophet for forecasting at Facebook_**

* Presenters: Sean Taylor, Ben Letham (Facebook)
* [Video](https://youtu.be/E8z3LObimok)
* [research.fb.com/facebook-at-stancon-2018](https://research.fb.com/facebook-at-stancon-2018/)
* [facebook.github.io/prophet](https://facebook.github.io/prophet/)


**_Stan applications in human genetics: Prioritizing genetic mutations that protect individuals from human disease_**

* Presenter: Manuel Rivas (Stanford University)
* [Video](https://youtu.be/S6FzGHPPxV4) 
* [Slides](2018/Invited-Talks/Rivas.pdf)
* [med.stanford.edu/rivaslab](http://med.stanford.edu/rivaslab.html)

**_Statistics using geometry to show uncertainties and integrate graph information_**

* Presenter: Susan Holmes (Stanford University)
* [Video]( https://youtu.be/W8TxxN8UdDQ)
* [Slides](2018/Invited-Talks/Holmes.pdf)
* [statweb.stanford.edu/~susan](http://statweb.stanford.edu/~susan/)

  
**_A brief history of Stan_** 

* Presenter: Daniel Lee (Generable)
* [Video](https://youtu.be/xJTZKawa-bM)
* [Slides](2018/Invited-Talks/Lee.pdf)
* [github.com/syclik](https://github.com/syclik)


**_Model assessment, model selection and inference after model selection_** 

* Presenter: Aki Vehtari (Aalto University)
* [Video](https://youtu.be/FUROJM3u5HQ)
* [Notebook, code, slides](https://github.com/avehtari/modelselection_tutorial) 
* [users.aalto.fi/~ave/](https://users.aalto.fi/~ave/)
  
  
**_Spatial models in Stan: intrinsic auto-regressive models for areal data_** 

* Presenter: Mitzi Morris (Columbia University)
* [Video](https://youtu.be/bwLkumivtjU)
* [Slides](2018/Invited-Talks/Morris.pdf)
* [Case study](http://mc-stan.org/users/documentation/case-studies/icar_stan.html)
* [github.com/mitzimorris](https://github.com/mitzimorris)

**_Some problems I'd like to solve in Stan, and what we'll need to do to get there_** 

* Presenter: Andrew Gelman (Columbia University) 
* [Video](https://youtu.be/uDB_NF_i5Ps)




<br>
  
## StanCon 2018 | August 29-31, Aalto University, Helsinki

### 2018 Helsinki Peer reviewed contributed talks


**_Solving ODEs in the wild: Scalable pharmacometrics with Stan_** 

* Authors: Weber, Sebastian (Novartis)

Pharmacometric modeling involves nonlinear hierarchical models, which
are most naturally expressed as forced ordinary differential equations
(ODEs). These class of models lead to a number of challenges which
complicate a practical modeling work-flow in Stan mostly due to long
model execution times. This contribution demonstrates at the example
of the drug Warfarin how forced ODEs can be written efficiently in
Stan leading to a doubling in model evaluation speed for the presented
example. Finally, it is demonstrated how the new `map_rect` facility
in Stan can be used to make models scalable to large data sets leading
to substantial speedups in model evaluation time and most importantly
this enables to *scale* Stan's performance as needed.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=wcpjZC9AV84&t=1h44m33s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/weber/stancon18-master) 

**_Analysis of repeated measures data in RStan_** 

* Authors: Munda, Marco (Pharmalex)

We illustrate the analysis of repeated measures data in the Bayesian framework using RStan.
In addition to the modelling itself, we further show how to make inference on the primary effect based on a probability of success, and how to predict the longitudinal profile of a future patient, two difficult (if not impossible) tasks from a frequentist perspective.

DOI link image goes here

Links: 

* Video not available
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/weber/stancon18-master) 

**_Define Custom Response Distributions with brms_** 

* Authors: Bürkner, Paul (University of Münster)

The **brms** package (Bürkner, 2017a, 2017b) implements Bayesian regression models using the probabilistic programming language **Stan** (Carpenter et al., 2016) behind the scenes. It has grown to be one of the most flexible R packages when it comes to multilevel regression modelling. A wide range of response distributions are supported, allowing users to fit -- among others -- linear, robust linear, count data, survival, response times, ordinal, zero-inflated, hurdle, and even self-defined mixture models all in a multilevel context. Predictor terms can be specified with a simple yet powerful formula syntax. Thanks to **Stan**, even very complex models tend to converge well in a reasonable amount of time. While **brms** comes with a lot of built-in response distributions (usually called *families* in R), there is still a long list of distributions which are not natively supported. The present notebook will explain how to specify such *custom families* in **brms**. By doing that, users can benefit from the modeling flexibility and post-processing options of **brms** even when applying self-defined response distributions.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=FoaxA7sJi7w&t=2h13m03s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/blob/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/buerkner/buerkner_notebook.Rmd) 


**_Are shots predictive of soccer results?_** 

* Authors: L.Egidi, F.Pauli, N.Torelli - University of Trieste, Italy

Predicting the outcome of a soccer match is the subject of much debate, and several models based on different assumptions 
have been proposed for modeling the numbers of goals scored by two competing teams. In this case study we adopt a different perspective and propose a Bayesian hierarchical model consisting of three nested multiple outcomes: 
**number of scores**, **number of shots on target** and **number of total shots**. We model the number of scores and the number of shots on target with  <span style="color:red">two binomial 
distributions</span> respectively, whereas the total shots follow a negative binomial distributon. Our dataset consists of nine seasons of the English Premier League (EPL): eight seasons---from 2008/2009 to 2015/2016, 3040 matches---represent the train set, whereas the nineth season, 2016/2017 (with the remaining 380 matches), is our test set, used for out-of sample prediction. 


DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=pKZLJPrZLhU&t=4h15m39s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/egidi/egidi) 


**_Self-tuning Holidays_** 

* Authors: Braylan, Alex 

We develop a flexible, portable, and interpretable Bayesian model of cyclical holiday effects on time series. Our model uses five parameters for each possible holiday that capture the general shape, magnitude, and peak location offset of each holiday effect. Choice of priors prevents the model from overfitting while still achieving considerable flexibility. We experiment on simulated and real data from Google Trends and demonstrate the model's performance on held-out data.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=FoaxA7sJi7w&t=18m15s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/braylan) 

**_Artificial Turf Advantage and Predictive Accuracy in Dutch Football_** 

* Authors: Verhoeven, Gertjan 

This submission uses Stan to learn about the so-called artificial turf advantage in Dutch football. Two model variants are used to model match outcomes. One of the models is the model from Milad Kharratzadeh presented at Stancon 2017, the other is new to Stan (a dynamic Skellam model). I use out-of-sample forecasts together with the Ranked Probability Score (a proper scoring rule) to learn whether including the artificial turf advantage increases predictive accuracy. Bookmakers odds are used as a benchmark to check the quality of our forecasts.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=pKZLJPrZLhU&t=4h40m34s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/verhoeven/artificial_turf_predictive-master) 

**_ODE Model of Gene Regulation_** 

* Authors: Modrák, Martin 

In this notebook we fit time series of gene expression data with a 
non-linear ODE-based model. Splines are used to model noisily observed 
regulator expression. The ODE is not solved explicitly, it is instead 
transformed to a definite integral and integrated via the trapezoid 
rule. Some interesting reparametrizations are introduced to make the 
model well identified.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=wcpjZC9AV84&t=1h24m10s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/modrak/genexpi-stan) 



**_Predicting New York City School Enrollment_** 

* Authors: Auerbach, Jonathan, Jones, Timothy and Winstanley, Robin (Columbia University)

We propose a Bayesian hierarchical Age-Period-Cohort model to predict elementary 
school enrollment in New York City. We demonstrate this model using student 
enrollment data for grades K-5 in each Census Tract of Brooklyn's 20th School 
District over the 2001-02 to 2010-11 school years. Specifically, our model 
disaggregates enrollment into grade (age), year (period), and cohort effects so 
that each can be interpreted and extrapolated over the 2011-12 to 2017-18 school 
years. We find this approach ideal for incorporating spatial information 
indicative of the socioeconomic forces that determine school enrollment in New 
York City.


DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=pKZLJPrZLhU&t=4h02m50s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/blob/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/auerbach_jones_winstanley/auerbach_jones_winstanley_notebook.Rmd) 

**_Analyzing Brain Taxonomy Trees_** 

* Authors: Hammill, Chris and Lerch, Jason

This talk and notebook introduce the idea of analyzing brain anatomy as a taxonomy of structures, defined by containment, using Stan. This taxonomy imposes dependence between model coefficients for structures and their enclosing structure. The slides and notebook compare this approach to other hierarchical modelling strategies using the mouse brain for illustration.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=pKZLJPrZLhU&t=2h18m48s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/hammill) 

**_Getting more out of Stan: some ideas from the Haskell bindings_** 

* Authors: Nielsen, Thomas A. (Tweag I/O), Steinitz, Dominic (Tweag I/O) and Nilsson, Henrik (School of Computer Science, University of Nottingham)

We present draft bindings to Stan in Haskell, a purely functional programming language. Unlike in most bindings, our models are encoded as a data type the host language. We show how this can be used to widen the range of computations that can be done based on the Stan model definition. For instance, predictions, posterior predictive checks and residual calculations can be done based on a single model definition.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=pKZLJPrZLhU&t=5h05m28s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/nielsen) 


**_Solving ODEs in the wild: Scalable pharmacometrics with Stan_** 

* Authors: Weber, Sebastian, Siivola, Eero (Statistical Methodology Group, Novartis Pharma AG)

Pharmacometric modeling involves nonlinear hierarchical models, which
are most naturally expressed as forced ordinary differential equations
(ODEs). These class of models lead to a number of challenges which
complicate a practical modeling work-flow in Stan mostly due to long
model execution times. This contribution demonstrates at the example
of the drug Warfarin how forced ODEs can be written efficiently in
Stan leading to a doubling in model evaluation speed for the presented
example. Finally, it is demonstrated how the new `map_rect` facility
in Stan can be used to make models scalable to large data sets leading
to substantial speedups in model evaluation time and most importantly
this enables to *scale* Stan's performance as needed.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=wcpjZC9AV84&t=1h24m10s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/weber/stancon18-master) 

**_Dose-finding clinical trial designs in Stan with trialr_** 

* Authors: Brock, Kristian 

My notebook illustrates two different methods for conducting dose-finding clinical trials.
The first, CRM, escalates dose according to toxicity outcomes only, assuming implicitly that higher doses are more likely to benefit the patient.
The second, EffTox, escalates dose according to efficacy and toxicity outcomes, thus addressing the potential that higher may not always mean better.
These models are implemented in the trialr R-package using Stan.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=FoaxA7sJi7w&t=2h32m49s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/brock) 

**_"The implementation of a model of choice: the (truncated) linear ballistic accumulator._** 

* Authors: Nicenboim, Bruno 

It is very common in cognitive science and psychology to use experimental tasks that involve making a fast choice among a restricted number of alternatives.  In this notebook, I focus on one influential and relatively simple model that belongs to the class of sequential-sampling models: the linear ballistic accumulator with a drift rate drawn from a normal distribution (restricted to positive values) (S. D. Brown and Heathcote 2008; Heathcote and Love 2012). First, I discuss the motivation for fitting this model using the Stroop task (Stroop 1935) as a case study. Then, I discuss the challenges in the implementation of the model in (R)Stan (Stan Development Team 2017), which might also apply to other hierarchical models with complex likelihood functions. Finally, I show some results that exemplify how the linear ballistic accumulator can be used for examining individual differences.


DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=pKZLJPrZLhU&t=1h46m05s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/nicenboim) 

**_Hierarchical Ornstein-Uhlenbeck type t-processes_** 

* Authors: Laitinen, Ville & Lahti, Leo (Open Research Labs, University of Turku)

This work investigates probabilistic time series models that are motivated by applications in statistical ecology. In particular, we investigate variants of the mean-reverting and stochastic Ornstein-Uhlenbeck (OU) process. We provide a hierarchical extension for joint analysis of multiple (short) time series, validate the model, and analyze its performance with simulations. The works extends the recent Stan implementation of the OU process (A 2018), where parameter estimates of a Student-t type OU process are obtained based on a single (long) time series. We have added a level of hierarchy, which allows joint inference of the model parameters across multiple time series.

DOI link image goes here

Links: 

* [Video](https://www.youtube.com/watch?v=pKZLJPrZLhU&t=2h05m53s)
* [Notebook, code, slides](https://github.com/stan-dev/stancon_talks/tree/stancon_2018_helsinki/2018-helsinki/Contributed-Talks/laitinen) 

**_Title_** 

* Authors: Names (Affiliations)

Blurb goes here

DOI link image goes here

Links: 

* Video
* [Notebook, code, slides](2018-helsinki/Contributed-Talks/01_lastname) 

 

### 2018 Helsinki Invited talks 

**_Title_**
    
* Presenter: Name (Affiliation)
* Video
* [Slides](2018/Invited-Talks/lastname) 
