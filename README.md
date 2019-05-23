# my-masters-degree-in-statistics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources for my custom-designed Master's degree in Statistics with a concentration in Machine Learning at Louisiana State University.     



# Contents

<!-- START_TOC -->

* [Contents](#contents)
* [Theory](#theory)
    * [Linear Algebra](#linear-algebra)
    * [Numerical Analysis](#numerical-analysis)
    * [Partial Differential Equations](#partial-differential-equations)
    * [Probability and Statistics](#probability-and-statistics)
* [Advanced Theory](#advanced-theory)
    * [Analysis](#analysis)
        * [Real Analysis](#real-analysis)
        * [Measure Theory](#measure-theory)
        * [Stochastic processes](#stochastic-processes)
    * [Convex Optimization](#statistical-learning)
* [Applied](#applied)
    * [Statistical Methods](#statistical-methods)
    * [Statistical Computing](#statistical-computing)
    * [Regression Analysis](#regression-analysis)
    * [Time Series Analysis](#time-series-analysis)
        * [Resampling Methods for Time Series](#resampling-methods-for-time-series) 
        * [Time Series Anomaly Detection](#time-series-anomaly-detection)    
    * [Design of Experiments](#design-of-experiments)
    * [Categorical Data Analysis](#categorical-data-analysis)
* [Advanced Applied](#advanced-applied)
    * [Computational Linear Algebra](#computational-linear-algebra)
    * [Bayesian Analysis](#bayesian-analysis)
    * [Multivariate Statistics](#multivariate-statistics)
    * [Statistical Machine Learning](#statistical-machine-learning)
    * [Deep Learning](#deep-learning)
    * [Network Analysis and Causal Inference](#network-analysis-and-causal-inference)
    * [Advanced Statistical Modelling](#advanced-statistical-modelling)
    * [Probabilistic Graphical Models](#probabilistic-graphical-models)
    * [Longitudinal Data Analysis](longitudinal-data-analysis)
    * [Survival and Reliability Analysis](survival-and-reliability-analysis)
    * [Databases](#databases)
* [Research](#research)
* [Personal and Practicuum Consulting Projects](#personal-and-practicuum-consulting-projects)    
* [MOOCs](#moocs) 
* [Society of Actuaries Exams](#society-of-actuaries-exams)
* [Miscs](#miscs)


<!-- END_TOC -->

***************
********************


# Theory

## Linear Algebra
Probably one of the top 3 most relevant areas of study for statisticians. You could get away with little knowledge in Abstract Algebra, but you really need to master Linear Algebra. Go beyond the usual algebraic matrix calculations - try to get a deep, almost philosphical view on concepts like projectivity, spectral decomposition, sparse matrices, etc.  

* [Linear Algebra](https://www.cs.cornell.edu/courses/cs485/2006sp/LinAlg_Complete.pdf) - Paul Dawkins (Cornell University)
* [MIT OpenCourseWare Lectures on Linear Algebra as Jupyter Notebooks](https://github.com/juanklopper/MIT_OCW_Linear_Algebra_18_06) - Juan Klopper
* [Introduction to Applied Linear Algebra](https://web.stanford.edu/~boyd/vmls/vmls.pdf) - Stephen Boyd (Stanford University), Lieven Vandenberghe (UCLA)
* [Introduction to vectors and tensors, Vol 1: linear and multilinear algebra](http://oaktrust.library.tamu.edu/handle/1969.1/2502) - Ray M Bowen, C. C. Wang
* [Introduction to vectors and tensors, Vol 2: vector and tensor analysis](http://oaktrust.library.tamu.edu/handle/1969.1/3609) - Ray M Bowen, C. C. Wang

********************

## Numerical Analysis

I HATED this subject as an undergrad - I don't recall why though :) Now, I can barely imagine computational statistics without some approximate or numerical solutions. Almost all statistical software provide numerical solutions to all probability distributions, simulation and optimization problems. Again over here, go beyond the usual undergrad numerical topics - at least try numerical implementations/solutions to eigen-problems, smoothing and optimization, splines, random number generation, and Monte Carlo Simulations. This subject also provides good practice in computing and design in general. 


* [A Concise Introduction to Numerical Analysis](http://www.ima.umn.edu/~arnold/597.00-01/nabook.pdf) - Douglas N. Arnold (University of Minnesota)
* [Introduction to Numerical Analysis](https://github.com/mandli/intro-numerical-methods) - Kyle Mandli (Columbia University)
* [Computational Numerical Analysis](http://www.engr.uky.edu/~acfd/egr537-lctrs.pdf) - J. M. McDonough (University of Kentucky)
* [Numerical Analysis for Engineers](https://ece.uwaterloo.ca/~dwharder/NumericalAnalysis/) - Douglas Wilhelm Harder  

********************

## Partial Differential Equations
Personally, this is the most exciting field in applied math that I have encountered so far. The overarching theme is the relationship between space and time variables to rates of change. I took this class because of its deep connections with uncertainty quantification, optimization, network analysis, image analysis and stochastic DEs (most notably, the Black-Sholes in Options Pricing).

* [Notes on Partial Differential Equations](https://www.math.ucdavis.edu/~hunter/pdes/pde_notes.pdf) - John K. Hunter (University of California at Davis)
* [Computational Numerical PDEs](https://github.com/mandli/numerical-methods-pdes) - Kyle Mandli (Columbia University)   
* [COOL Applications](https://math.berkeley.edu/~sethian/2006/Applications/Menu_Expanded_Applications.html) - by Jamie Sethian (UC - Berkeley)


********************

## Probability and Statistics

Well, this section is self-explanatory. I will recommend you thoroughly understand the following concepts: Transformations, Independency and Copulas, Convergence, Sufficiency, Parameter Estimation and Inference, and the Exponential Family of Distributions. Dr. Luis Escobar of LSU has amazing lecture notes on these topics.

* [Statistical Inference](https://www.amazon.com/Statistical-Inference-George-Casella/dp/0534243126) - Casella and Berger
* [Stat 414/415](https://newonlinecourses.science.psu.edu/stat414/) - Penn State
* [Introduction to Probability](http://vfu.bg/en/e-Learning/Math--Bertsekas_Tsitsiklis_Introduction_to_probability.pdf) - Dimitri P. Bertsekas, John N. Tsitsiklis (MIT)
* [A Short Introduction to Probability](http://www.maths.uq.edu.au/~kroese/asitp.pdf) - Dirk P. Kroese (University of Queensland)
* [Probability: Theory and Examples](https://www.math.duke.edu/~rtd/PTE/PTE4_1.pdf) - Rick Durrett
* [Probability and Statistics Cookbook](https://github.com/mavam/stat-cookbook/releases/download/0.2.3/stat-cookbook.pdf) - Matthias Vallentin (UC Berkeley)


********************
********************

# Advanced Theory
Here are the bitter pills that you just have to swallow :)


## Analysis

### Real Analysis

* [MIT OpenCourseWare Lectures on Calculus](https://ocw.mit.edu/resources/res-18-001-calculus-online-textbook-spring-2005/textbook/) - G. Strang
* [An Introduction to Real Analysis](https://www.math.ucdavis.edu/~hunter/intro_analysis_pdf/intro_analysis.pdf) - John K. Hunter (University of California at Davis)
* [Introduction to Real Analysis](http://ramanujan.math.trinity.edu/wtrench/texts/TRENCH_REAL_ANALYSIS.PDF) - William F. Trench (Trinity University, Texas)
* [Basic Analysis: Introduction to Real Analysis](http://www.jirka.org/ra/realanal.pdf) - Jiří Lebl
* [Elementary Real Analysis](http://prac.im.pwr.wroc.pl/~kwasnicki/pl/stuff/tbb-hyper.pdf) - Thomson, Bruckner
* [Lecture Notes in Real Analysis](http://ms.mcmaster.ca/~sawyer/Publications/Real_Analysis.pdf) - Eric T. Sawyer (McMaster University)
* [Real Analysis](http://math.harvard.edu/~ctm/papers/home/text/class/harvard/212a/course/course.pdf) - C. McMullen
* [Real Analysis for Graduate Students](http://bass.math.uconn.edu/3rd.pdf) - Richard F. Bass
* [Modern Real Analysis](http://www.math.purdue.edu/~torres/pubs/Modern-real-analysis.pdf) - William P. Ziemer (Indiana University)
* [Mathematical Analysis Vol I](http://www.trillia.com/zakon-analysisI.html) - Elias Zakon


********************

### Measure Theory

* [An Introduction to Measure Theory](https://terrytao.files.wordpress.com/2011/01/measure-book1.pdf) - Terence Tao (UCLA)
* [Lecture Notes in Measure Theory](http://www.math.chalmers.se/~borell/MeasureTheory.pdf) - Christer Borell
* [A Crash Course on the Lebesgue Integral and Measure Theory](http://www.gold-saucer.org/math/lebesgue/lebesgue.pdf) - Steve Cheng
* [Measure Theory](https://www.math.ucdavis.edu/~hunter/measure_theory/measure_notes.pdf) - John K. Hunter (University of California at Davis)
* [Measure and Integration](https://people.math.ethz.ch/~salamon/PREPRINTS/measure.pdf) - Dietmar A. Salamon (ETH Zürich)

********************

### Stochastic Processes 

* [Stochastic Processes (Advanced Probability II)](https://www.stat.cmu.edu/~cshalizi/754/) - Cosma Shalizi (Carnegie Mellon University)  
* [Stochastic Models and Simulation](https://wolfweb.unr.edu/~drschmidt/Stat753/) - Deena Schmidt(University of Nevada, Reno)


********************
********************

## Convex Optimization 

This subject is a MUST.

* [Convex Optimization](https://see.stanford.edu/Course/EE364A) - Stephen P. Boyd (Stanford University)  
* [Convex Optimization](http://www.stat.cmu.edu/~ryantibs/convexopt/) - Ryan Tibshirani (Carnegie Mellon University)

********************
********************

# Applied

## Statistical Methods

This was mostly a slightly refined version of undergrad statistical methods with little bit of design of experiments. This class, I believe, was designed for grad students with little to no background in math/stats. For folks with some stats background, I highly recommend the resources below especially Cosma Shalizi's book, which is hands down, the best introductory stats book I have ever read.   

* [Advanced Data Analysisfrom an Elementary Point of View](https://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/ADAfaEPoV.pdf) - Cosma Shalizi (Carnegie Mellon University)
* [Statistical Methods: The Geometric Approach](https://www.springer.com/us/book/9780387975177?gclid=EAIaIQobChMIkP7_gPOv4gIVEpJbCh1A2gFMEAQYAiABEgIoqPD_BwE) - Alan Agresti (University of Florida)
* [Applied Linear Models](https://mysite.science.uottawa.ca/rkulik/mat3378/mat3378-textbook.pdf) - Kutner et al.
* [Design of Experiments](https://newonlinecourses.science.psu.edu/stat503/) - Penn State
* [Applied Statistics with R](https://daviddalpiaz.github.io/appliedstats/) - David Dalpiaz (University of Illinois - Urbana Champaign)

********************

## Statistical Computing 

Some of these are more 'pseudo' than actual statistical computing, but very useful content all the same. 

* [Statistical Computing Methods](http://www.markirwin.net/stat221/) - Mark Irwin (Harvard University)
* [Statistical Computing](http://www.stat.cmu.edu/~ryantibs/statcomp/) - Ryan Tibshirani (Carnegie Mellon University)  
* [Statistical Computing](https://www.stat.cmu.edu/~cshalizi/statcomp/14/) - Cosma Shalizi (Carnegie Mellon University)  

********************

## Regression Analysis 

This stand-alone class on regression is one of the best classes I took at LSU. The professor,  Dr. Brian Marx, effortlessly walks you through the rationale behind the nitty-gritties of regression and generalized modelling in general. You do not want to miss his classes. Alan Agresti's book below is invaluable!  


* [Regression: Models, Methods and Applications](https://www.springer.com/us/book/9783642343322) - B.D. Marx et al.
* [Introduction to Linear Regression Analysis 5th Edition](https://www.amazon.com/Introduction-Regression-Analysis-Douglas-Montgomery/dp/0470542810) - Montgomery et al.
* [The Truth About Linear Regression](www.stat.cmu.edu/~cshalizi/TALR/TALR.pdf) - Cosma Shalizi (Carnegie Mellon University)
* [Foundations of Linear and Generalized Linear Models](https://www.oreilly.com/library/view/foundations-of-linear/9781118730058/) - Alan Agresti (University of Florida)

********************

## Time Series Analysis  

Best taken after after the modules on Generalized Linear Models. I found Dr. Robert Nau's notes on Time Series Analysis particularly useful. Dr Shalizi does an equally good job but relatively introductory. 

* [Statistical Forecasting: Regression and Time Series](http://people.duke.edu/~rnau/411home.htm) - Robert Nau (Duke University)
* [Data over Space and Time](http://www.stat.cmu.edu/~cshalizi/dst/18/) - Cosma Shalizi(Carnegie Mellon University)
* [Forecasting: Principles and Practice](https://otexts.com/fpp2/) - by [R. J. Hyndman](https://github.com/robjhyndman) and G. Athanasopoulos
* [Time Series Analysis](https://ocw.mit.edu/courses/economics/14-384-time-series-analysis-fall-2013/) - Standford University
* [Time Series Analysis - GitHub R Codes Repo](https://github.com/nickpoison/tsa4)
* [Little Book of R for Time Series](https://a-little-book-of-r-for-time-series.readthedocs.io/en/latest/)
* [Interesting Examples from Peter Laurinec](https://petolau.github.io/)
* [Example: Time Series with GAM](https://petolau.github.io/Analyzing-double-seasonal-time-series-with-GAM-in-R/)


### Resampling Methods for Time Series

* [Paper: Resampling strategies for imbalanced time series forecasting](https://link.springer.com/article/10.1007/s41060-017-0044-3) -  Moniz et al. 2017.
* [Paper: The Impact of Bootstrap on Time Series Data](www.math.ucsd.edu/~politis/StatSci03.pdf)
* [Example: Time Series Cross Validation](https://rpubs.com/crossxwill/time-series-cv)
* [Example: Time Series Cross Validation](https://robjhyndman.com/hyndsight/tscv/)


### Time Series Anomaly Detection

I selected the most useful to me from this [exhaustive list](https://github.com/yzhao062/anomaly-detection-resources)   

* [Outlier Analysis](https://www.springer.com/us/book/9781461463955) - Aggarwal, Charu C.
* [Outlier Ensembles: An Introduction](https://www.springer.com/us/book/9783319547640) - Aggarwal, Charu C., Sathe, Saket
* [Anomaly Detection: A Tutorial](webdocs.cs.ualberta.ca/~icdm2011/downloads/ICDM2011_anomaly_detection_tutorial.pdf)



### Some Anomaly Detection Software


| Name          | Language       | Pitch     | License
| ------------- |:-------------: | :-------------: |  :-------------:     
| Twitter's [AnomalyDetection](https://github.com/twitter/AnomalyDetection)| R      |AnomalyDetection is an open-source R package to detect anomalies which is robust, from a statistical standpoint, in the presence of seasonality and an underlying trend.   | GPL
| Linkedin's [luminol](https://github.com/linkedin/luminol)                | Python |Luminol is a light weight python library for time series data analysis. The two major functionalities it supports are anomaly detection and correlation.| Apache-2.0      
| [Donut](https://github.com/korepwx/donut)| Python | Donut is an unsupervised anomaly detection algorithm for seasonal KPIs, based on Variational Autoencoders. | -
| NASA's [Telemanom](https://github.com/khundman/telemanom)| Python | A framework for using LSTMs to detect anomalies in multivariate time series data. Includes spacecraft anomaly data and experiments from the Mars Science Laboratory and SMAP missions.  | [custom](https://github.com/khundman/telemanom/blob/master/LICENSE.txt)
| [banpei](https://github.com/tsurubee/banpei)| Python | Outlier detection (Hotelling's theory) and Change point detection (Singular spectrum transformation) for time-series. | MIT
| [CAD](https://github.com/smirmik/CAD) | Python | Contextual Anomaly Detection for real-time AD on streaming data (winner algorithm of the 2016 NAB competition). | AGPL



********************

## Design of Experiments

Maybe the MVP in the entire masters program. With the current era of 'big data', there is uneccessarily high focus on prediction, but prediction in itself is sometimes useless without control. Randomized experiments is one way to test competing ideas or solutions, and thus control predictions or outcomes. The professor of this course, Dr. David C. Blouin is a seasoned expert in experimental design. I recommend taking this class after taking the linear modelling and or data mining classes because this class (DOE) introduces an almost artistic yet scientific paradigm to problem solving which you would not appreciate if taken prior to taking the latter classes. This class is project-heavy - roughly 2 projects every week - which helps in honing this almost artistic skill.   


Although not necessary, I recommend you take this class simultaneously with an introductory course in **Causal Inference**.

* [Design of Experiments](https://www.springer.com/us/book/9783319522487?gclid=EAIaIQobChMIkPbZq_mv4gIVjbbACh1vLggzEAQYAiABEgJ05_D_BwE) - Dean et al.
* [Desgin of Experiments](http://statweb.stanford.edu/~owen/courses/363/) - Stanford University 
* [Design and Analysis of Experiments - GitHub Repo](https://github.com/fcampelo/Design-and-Analysis-of-Experiments)
* [Elements of Causal Inference: Foundations and Learning Algorithms ](https://mitpress.mit.edu/books/elements-causal-inference) - Peters et al.
* [Online Experiments for Computational Social Science](https://eytan.github.io/www-15-tutorial/) - Eytan Bakshy and Sean J. Taylor 
* [A Crash Course in Causality: Inferring Causal Effects from Observational Data](https://www.coursera.org/learn/crash-course-in-causality)


********************

## Categorical Data Analysis

Again Dr. Brian D. Marx does a masterful job at teaching this class. This class introduces the concepts of Generalized Linear Modelling, with the latter half of the class focusing mainly on the analysis of categorical/discrete data. 

* [Categorical Data Analysis](https://www.wiley.com/en-us/An+Introduction+to+Categorical+Data+Analysis%2C+3rd+Edition-p-9781119405269) - Alan Agresti (University of Florida)
* [Resources for Alan Agresti's Books](http://users.stat.ufl.edu/~aa/cda/cda.html)
* [Analysis of Categorical Data with R](http://www.chrisbilder.com/categorical/index.html) - Christopher R. Bilder (University of Nebraska-Lincoln)
* [Analysis of Discrete Data](https://newonlinecourses.science.psu.edu/stat504/node/4/) - Penn State
* [Generalized Linear Models](http://www.markirwin.net/stat149/) - Mark Irwin (Harvard University)
* [Some Projects](https://github.com/topics/categorical-data)


*****************
******************


# Advanced

## Computational Linear Algebra

Basically numerical methods to linear algebra

* [Computational Linear Algebra with Python](https://github.com/fastai/numerical-linear-algebra)
* [Computational Linear Algebra Videos](https://www.youtube.com/playlist?list=PLtmWHNX-gukIc92m1K0P6bIOnZb-mg0hY) - Rachel Thomas

******************

## Bayesian Analysis

I struggled in this class partly because I had a terrible load of 18 credits that semester - which is A LOT for graduate shool. I spent the subsequent semester vacation reviewing the material and I found it surprisingly easy. I found reading materials from other schools and practicing the coding very useful. 

* [Bayesian Methods and Modern Statistics - Course GitHUb Repo](https://github.com/resteorts/modern-bayes) - Rebecca Steorts (Duke University) 
* [Bayesian Methods and Modern Statistics - Course Website](http://www2.stat.duke.edu/~rcs46/bayes18.html) - Rebecca Steorts (Duke University)
* [Applied Bayesian Analysis](https://www4.stat.ncsu.edu/~reich/ABA/index.html) - Brian Reich (North Carolina State University)
* [Bayesian Inference](https://www4.stat.ncsu.edu/~reich/ST740/) - Brian Reich (North Carolina State University)
* [Think Bayes](http://greenteapress.com/wp/think-bayes/) - Allen B. Downey
* [Probabilistic Programming and Bayesian Methods for Hackers - GitHub Repo](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Cameron Davidson-Pilon
* [Bayesian Modelling with Python](https://github.com/markdregan/Bayesian-Modelling-in-Python)
* [Probabilistic Programming and Bayesian Methods for Hackers - Website](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) - Cameron Davidson-Pilon
* [Bayesian Modeling and Inference](https://people.eecs.berkeley.edu/~jordan/courses/260-spring10/) - Michael Jordan(UC - Berkeley)
* [Learning Bayes](http://florianhartig.github.io/LearningBayes/)

*************************

## Multivariate Statistics

* [Applied Multivariate Methods for Data Analysts](https://www.amazon.com/Applied-Multivariate-Methods-Data-Analysts/dp/0534237967) - Dallas E. Johnson
* [A First Course in Structural Equation Modeling, 2nd ed.](https://www.amazon.com/First-Course-Structural-Equation-Modeling/dp/0805855882) - Tenko et al.
* [Applied Multivariate Analysis](https://onlinecourses.science.psu.edu/stat505/) - Penn State
* [Nonlinear Models for Univariate and Multivariate Response](https://www.stat.ncsu.edu/people/davidian/courses/st762_fall2009//) - Marie Davidian (NC State University)


************************* 


## Statistical Learning 

With the recent 'Data Science' craze there is a litany of dumbed-down materials on SL. Although good for beginners, these are woefully lacking for statisticians hoping to engineer new methodologies, improve or critique current techniques.  

Dive into these as much as you can - they are the best materials on Introduction to Statistical Machine Learning out there. Take key note of concepts regarding **RE-presentation** of data, and projectivity.

* [Advanced Topics in Statistical Modelling](http://statweb.lsu.edu/faculty/li/teach/exst7152/) - Bin Li (Louisiana State University)
* [Statistical Machine Learning](http://www.stat.cmu.edu/~ryantibs/statml/) R. Tibshirani and L. Wasserman (Carnegie Mellon University)
* [Data Mining](https://www.stat.cmu.edu/~cshalizi/350/) Cosma Shalizi (Carnegie Mellon University)
* [An Introduction to Statistical Learning with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf) - Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani
* [Computer Age Statistical Inference](https://web.stanford.edu/~hastie/CASI/) - Bradley Effron and Trevor Hastie
* [MOOC: Outlier Detection Algorithms in Data Mining and Data Science](https://www.udemy.com/outlier-detection-techniques/)
* [Blog Post: Winning Solutions - Kaggle Competitions](https://www.kaggle.com/sudalairajkumar/winning-solutions-of-kaggle-competitions)

********************

## Deep Learning 

* [Machine Learning - Stanford](https://class.coursera.org/ml-005) by Andrew Ng in Coursera (2010-2014)
* [Deep Learning with Python](faculty.neu.edu.cn/yury/AAI/Textbook/Deep%20Learning%20with%20Python.pdf) - Francois Chollet
* [Deep Learning](http://www.deeplearningbook.org/) by Yoshua Bengio, Ian Goodfellow and Aaron Courville  (05/07/2015)
* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) by  Michael Nielsen (Dec 2014)
* [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/)
* [Artificial intelligence and machine learning: Topic wise explanation](https://leonardoaraujosantos.gitbooks.io/artificial-inteligence/)
* [MOOC: Advanced Deep Learning with Keras](https://www.datacamp.com/courses/advanced-deep-learning-with-keras-in-python) by [Zach Mayer](https://github.com/zachmayer)

*******************

## Network Analysis and Causal Inference

* [Statistical Network Analysis](https://www.stat.cmu.edu/~cshalizi/networks/16-1/) - Cosma Shalizi (Carnegie Mellon University)
* [Advanced Statistical Network Models](https://www.stat.cmu.edu/~cshalizi/networks/16-2/) - Cosma Shalizi (Carnegie Mellon University)
* [Social and Information Network Analysis](http://snap.stanford.edu/class/cs224w-2016/handouts.html) - Jure Leskovec (Stanford University)
* [Networks, Crowds, and Markets: Reasoning About a Highly Connected World](http://www.cs.cornell.edu/home/kleinber/networks-book/) -  David Easley and Jon Kleinberg
* [Statistical Analysis of Network Data with R](https://link.springer.com/book/10.1007%2F978-1-4939-0983-4) - Eric D. KolaczykGábor Csárdi
* [Bayesian Networks: With Examples in R](https://www.crcpress.com/Bayesian-Networks-With-Examples-in-R/Scutari-Denis/p/book/9781482225587) - Marco Scutari, Jean-Baptiste Denis
* [Data Science and Complex Networks
Real Case Studies with Python](https://global.oup.com/academic/product/data-science-and-complex-networks-9780199639601?cc=us&lang=en&) - Guido Caldarelli and Alessandro Chessa
* [A Crash Course in Causality: Inferring Causal Effects from Observational Data](https://www.coursera.org/learn/crash-course-in-causality)  
* [Example: Exponential Random Graph Modelling](http://rstudio-pubs-static.s3.amazonaws.com/329810_72b09e66276044949bc3bdc2cfcd6161.html)


*******************


## Advanced Statistical Modelling

* [Advanced Topics in Statistical Modelling](http://statweb.lsu.edu/faculty/li/teach/exst7152/) - Bin Li (Louisiana State University)
* [Chaos, Complexity, and Inference](https://www.stat.cmu.edu/~cshalizi/462/) - Cosma Shalizi (Carnegie Mellon University)
* [Statistical Methods for Analysis With Missing Data](https://www4.stat.ncsu.edu/~davidian/st790/) - Marie Davidian(NC State University)
* [Example: Preprocessing Data with Caret](http://rismyhammer.com/ml/Pre-Processing.html)
* [Paper: Flexible Smoothing with B-Splines and Penalties](https://projecteuclid.org/euclid.ss/1038425655) - Paul H. C. Eilers and Brian D. Marx
* [Paper: Importance Sampled Learning Ensembles](http://statweb.stanford.edu/~jhf/ftp/isle.pdf) - Friedman and Popescu
* [Paper: Gradient Directed Regularization](http://statweb.stanford.edu/~jhf/ftp/pathlite.pdf) - Friedman and Popescu
* [Paper: Predictive Learning vis Rule Ensembles](http://statweb.stanford.edu/~jhf/ftp/RuleFit.pdf) - Friedman and Popescu
* [Paper: Kernels and Ensembles: Perspectives on Statistical Learning](http://www.math.uwaterloo.ca/~m3zhu/papers/TAS2008.pdf) - Mu Zhu
* [Book: Generalized Additive Models: An Introduction with R, Second Edition](https://www.crcpress.com/Generalized-Additive-Models-An-Introduction-with-R-Second-Edition/Wood/p/book/9781498728331) - Simon N. Wood
* [Simon Wood's Website](https://people.maths.bris.ac.uk/~sw15190/)
* [MOOC: Nonlinear Models with GAM](https://www.datacamp.com/courses/nonlinear-modeling-in-r-with-gams)
* [Example: An introduction to Generalized Additive Models with R](https://github.com/gavinsimpson/gams-yorku-canada-150)
* [Example: Generalised Additive Mixed Models](https://github.com/stefanocoretta/gamm-workshop/blob/master/gamm-presentation.pdf)
* [Paper: Convex Regression With Interpretable Sharp Partitions](http://jmlr.org/papers/v17/15-344.html) - Ashley Petersen, Noah Simon, Daniela Witten

*************************

## Probabilistic Graphical Models  

* [Probabilistic Graphical Models](https://cs.stanford.edu/~ermon/winter17-cs228/index.html) - Stefano Ermon (Stanford University)
* [Probabilistic Graphical ModelsProbabilistic Graphical Models](http://www.cs.cmu.edu/~epxing/Class/10708-14/lecture.html) - Eric Xing (Carnegie Mellon University)

**********************

## Longitudinal Data Analysis

I took this class simultaneously with Dr. Kevin S. McCarter's Multivariate Analysis.  

* [Longitudinal Data Analysis](https://www4.stat.ncsu.edu/~davidian/st732/) - Marie Davidian(NC State University)
* [Applied Multivariate and Longitudinal Data Analysis](https://www.stat.ncsu.edu/people/staicu/courses/st495-590/index.html)


*************************

## Survival and Reliability Analysis

Spontaneous and somewhat hobby-like reading on:

* [Introduction to Survival Analysis](https://lifelines.readthedocs.io/en/latest/Survival%20Analysis%20intro.html)   


I have also been trying to learn how to model survival data with Deep Learning algorithms by reading some of the papers (see link below) whenever I can. 

* [Survial Analysis using Deep Learning](https://github.com/robi56/Survival-Analysis-using-Deep-Learning/blob/master/README.md)

*************************

## Databases 
* [Database Systems - Carnegie Mellon University](https://15445.courses.cs.cmu.edu/fall2018/)
* [Introduction to Databases - Stanford Lagunita](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/)

*************************
*************************


# Research 

soon...

*************************
# Personal and Practicuum Consulting Projects  

soon...

*************************

# MOOCs
soon...

*************************

# Society of Actuaries Exams

soon...

*************************

# Miscs

soon...

*************************
*************************