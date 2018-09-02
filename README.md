# Hundred_Days_ML
Keeping track of ML studies, simulations, articles, books and papers read. Starting date: July 16, 2018.

* Computer Age Statistical Inference by Efron, Hastie
* Finish "Fundamentals of Machine Learning" from SanDiego [edX]
* Fluent Python by Ramalho
* Learning Python by Ascher, Lutz
* Prepare Data Mining Lab Handbook for the fall
* Bayesian Reasoning and Machine Learning by Barber (not quite sure)


### Day -5: July 11, 2018 (Wednesday)
* [mlr](https://github.com/mlr-org/mlr/blob/tutorial_pdf_dev/vignettes/tutorial/devel/pdf/mlr-tutorial_dev.pdf): machine learning in R (half of the tutorial)
* Transferring XGBoost to mlr architecture
* [Talk](https://www.youtube.com/watch?v=d1PnFiN6nOQ) on Data Mining as Exploratory Analysis (mlr)
* Record the most recent presentation on Machine Learning

### Day -4: July 12, 2018 (Thursday)
* XGBoost with Bayesian Optimization of hyperparameters [Adore Me]
* 4 hours of Advanced Python (see [Learning Python Repository](https://github.com/bizovi/hundred_days_ml))
* [Talk](https://www.youtube.com/watch?v=8o0e-r0B5xQ&t=647s) and Notes on Catboost algorithm developed by Yandex

**---Three days vacation in Italy---**


### Day 1: July 16, 2018 (Monday)
**Activity**: 
* Failed proof of concept of [Catboost](https://tech.yandex.com/catboost/doc/dg/concepts/r-quickstart-docpage/)
* Narrowed the selection of books to study this summer
* Started walking through Arthur Carpentier's [Classification from Scratch](https://freakonometrics.hypotheses.org/52731)
* Red [reviews](https://web.stanford.edu/~hastie/CASI_files/PDF/casi.pdf) of Efron's CASI, Introduction
* [Podcast](https://www.buzzsprout.com/147669/744363) from McKinzie's Data Science Consultant on Organizational Change
* Read 5 Mark Edmondson [articles](http://code.markedmondson.me/) on Data Science infrastructure in Google Cloud

**Notes**: Logistic regression is far far from finished. Need to:
* Generalize the functions
* Plot prediction regions via ggplot
* Refresh and work out the mathematical derivation


### Day 2: July 17, 2018 (Tuesday)

**Activity**:
* Implemented [Random Survival Model](https://kogalur.github.io/randomForestSRC/) for Churn Prediction on a small dataset
* Started working on [King County](https://www.kaggle.com/harlfoxem/housesalesprediction/kernels) House Prices prediction
* Talk on [Image Processing](https://www.youtube.com/watch?v=3HOulHAUhQw) for Biochemistry
* Reading from [CASI](http://web.stanford.edu/~hastie/CASI/order.html) for an hour [NOT DONE]

**Notes**: Make a plan to extract the maximum out of the House Pricing dataset (check). Problem with Survival Random Forests: Most of the covariates of interest are time-varying, not known before the ``experiment``, i.e. first purchase and it seems not to support it, although I'm sure it is possible to hack the way around this.


### Day 3: July 18, 2018 (Wednesday)

**Activity**:
* Talk by Lucas Bernardi on [Selection Bias: The elephant in the room](https://www.youtube.com/watch?v=3ZWCKr0vDtc&index=82&list=PLYEK5GJ_Xl7OPrucJhQ32RjafRyEdt5iT) and Propensity Modeling
* King County House pricing implementation [Exploratory Data Analysis]
* ggmap and visualizing geographical data

**Notes**: First unit test in production! R's `ggmap` is amazing.


### Day 4: July 19, 2018 (Thursday)

**Activity**:
* 4 hours of Advanced Python (see [Learning Python Repository](https://github.com/bizovi/hundred_days_ml)). Multithreading and Semaphores, Multiprocessing, Async Programming, Unit Testing
* King County House pricing blog post preparation
* Wrote 5 Unit Tests and refactored BigQuery helper functions

**Notes**: Was too exhausted to read a few pages from CASI


### Day 5: July 20, 2018 (Friday)

**Activity**:
* King County House pricing blog writing and polishing
* Efron and Hastie CASI Chapter One and Two

**Notes**: Reformat the markdown for [bizovi.github.io](https://bizovi.github.io)

### Day 6: July 21, 2018 (Saturday)

**Activity**:
* King County House Prices Exploratory Data Analysis for the blog
* Moscow [flats](https://www.coursera.org/learn/ekonometrika) dataset exploration for the blog
* Computerophile on [Convolutional Neural Networks](https://www.youtube.com/watch?v=BFdMrDOx_CM), [Deep Learning](https://www.youtube.com/watch?v=TJlAxW-2nmI) Video Streaming, [Lambda Calculus](https://www.youtube.com/watch?v=eis11j_iGMs)

**Notes**: Prepare for the long road by downloading SanDiego Machine Learning Fundamentals Course Videos.

**---Trip to New York---**

### Day 7: July 22, 2018 (Sunday)

**Activity**:
* Data Science in the Google Cloud from Chapter 3 forward (pag 1-180)
* More editing on house prediction challenges
* Presentations on [Feynman's lost lecture](https://www.youtube.com/watch?v=xdIjYBtnvZU), [Fermat's Last Theorem](https://www.youtube.com/watch?v=nUN4NDVIfVI&t=1489s) and two "bridges", [Convolutional Neural Networks](https://www.youtube.com/watch?v=py5byOOHZM8)

**Notes**: Compute Engine, AppEngine, Data Studio, BigQuery, DataLab, DataFlow, PubSub. Time spent mostly on the road.


### Day 8: July 23, 2018 (Monday)

**Activity**:
* Read Chapter 3 from CASI
* Read Paper on Defensive Programming in R ([checkmate](https://mllg.github.io/checkmate/))

**Notes**: Unit testing and TDD is appropriate for production stage of ML, in exploratory stages it is rather counter-productive.


### Day 9: July 24, 2018 (Tuesday)

**Activity**:
* Read Chapter 4 from CASI
* Talk on [Churn](https://www.youtube.com/watch?v=Fa3Ha6QYp3o&t=1504s) Analysis from booking using ML and Survival Analysis

**Notes**: On a right track with the dual approach of Classification and Survival analysis for Churn.


### Day 10: July 25, 2018 (Wednesday)

**Activity**:
* Read Chapter 5 from CASI
* Automating feature preprocessing pipelines considering temporal constraints

**Notes**: Exponential family for statistical infenece: connect with Ghrahramani's presenation.

### Day 11: July 26, 2018 (Thursday)

**---Night Out Driking---**

**Notes**: Catch up on Week Four of Advanced Python Course

### Day 12: July 27, 2018 (Friday)

**Activity**:
* Read Chapter 6 from CASIs
* Bayesian Logistic Regression in rstanarm by [Aki Vehtari](https://www.kaggle.com/avehtari/bayesian-logistic-regression-with-rstanarm) on Prima Indians dataset
* Horseshoe prior [paper](https://arxiv.org/abs/1610.05559) by Aki Vehtari

**Notes**: `rstanarm` and its vignettes are a good place to get started

### Day 13: July 28, 2018 (Saturday)

**Activity**:
* Consolidate knowledge from Chapter 1 to Chapter 6 CASI
* Bayesian Reasoning and Machine Learning Intro and Chapter 1

**Notes**: **---Visit in Jersey---**


### Day 14: July 29, 2018 (Sunday)

**Activity**:
* Publish King County EDA
* Catch up on Week Four of Advanced Python [Course](http://cursuri.telacad.ro/)
* Improve on [Classification from Scratch](https://freakonometrics.hypotheses.org/52731) Carpentier Part 0 and 1
* [Talk](https://www.youtube.com/watch?v=KFE039xtYJU) on Tips, Tricks and topics in text analysis

**Notes**: Dust off the theory and derivations behind Logistic Regression

### Day 15: July 30, 2018 (Monday)

**Activity**:
* Sliding window methodology for Churn Modeling
* Make a package with Google Cloud Helper functions
* Different modeling configuration of available history of purchases and prediction horizon.

**Notes**: Documentation with roxygen2 and best practices refresher for package building


### Day 16: July 31, 2018 (Tuesday)

**Activity**:
* Connect Chapter 6 CASI with David Robinson's [pamphlet](http://varianceexplained.org/r/empirical_bayes_baseball/) on Empirical Bayes
* Solve Barber's BRML Chapter One puzzles, carefully review notations and work out examples
* Investigate ways ML and Statistics can be used for optimizations in a Warehouse 

**Notes**: **---Visit at Adore Me Warehouse---**

### Day 17: August 1, 2018 (Wednesday)

**Activity**:
* Oversampling with [SMOTE](https://arxiv.org/pdf/1106.1813.pdf) for dealing with class imbalance with [mlr](https://arxiv.org/pdf/1609.06146.pdf)
* Bias-Variance diagnostics on Train-Test-Prod Churn datasets
* Computerophile video on [timezones](https://www.youtube.com/watch?v=-5wpm-gesOY)

### Day 18: August 2, 2018 (Thursday)

**Activity**:
* Survival analysis presentation
* Survival analysis Part One
* Gave a talk on Stats and Machine Learning for Decoding Customer Behavior
* Catch up on Advanced Python's Week 5 Course 

**Notes**: **---Ping-pong place---**

### Day 19: August 3, 2018 (Friday)

**Activity**:
* Survival Analysis Part Two (Multidimensional Analysis), Three (Time Varying Covariates), Four (Advanced Topics)
* Survival analysis with time-varying predictors (R paper)
* Learning Python ed. V. Introduction

**Notes**: Try Survival Random Forests with time-varying predictors (treating them as iid when they are hierarchical).

### Day 20: August 4, 2018 (Saturday)

**Activity**:
* Finally Publish the Blog Post with EDA for King County home prices prediction
* Investigate differences between STAN and PyMC3
* Bayesian Survival Analysis in PyMC3: four articles as examples

**Notes**: At the moment survival analysis looks like the most promising tool, especially when Classification methods are unable to find a meaningful pattern even in training datasets.

### Day 21: August 5, 2018 (Sunday)

**Activity**: 
* CASI Chapter 7 Reading
* Barber's BRML Chapter Two reading
* Week Two programming assignments from SanDiego ML Fundamentals

**Notes**: Reconsidering if a PhD is worth it and choices made until now.


### Day 22: August 6, 2018 (Monday)

**Activity**: 
* Survival Analysis for Churn Prediction in Game Industry
* Conditional Survival Ensembles
* WTTE-RNN for Churn Prediction
* WTTE-RNN Thesis by Egil Martinsson

**Notes**: As Egil Martinsson emphasizes, most of the ways of predicting churn are hack-ish. It's a nice area of investigation, trying to extend the classical time to event models.

### Day 23: August 7, 2018 (Tuesday)

**Activity**: 
* Wrangle Customer Care data to improve model predictions.
* Feature Engineering for Churn Model
* Brainstorming on ways in which to derive more meaningful features

**Notes**: Precision and Recall are not yet satisfactory, which means more resourcefulness in feature engineering.

### Day 24: August 8, 2018 (Wednesday)

**Activity**: 
* Undersampling for imbalanced classes with high Bayes Error
* Evaluating model performance by Train, Test, Production via AUC, Recall and Precision
* Experiment with Bayesian Additive Regression trees for classification. Investigate variable importance and diagnostics.

**Notes**: For large datasets in BartMachine, in order not to run out of memory, one has to disable caching and evaluation of peformance metrics. One wrong step and the Java will be out of memory.

### Day 25: August 9, 2018 (Thursday)

**Activity**: 
* Bang my head on ExactTarget's opaque Automation Studio. 
* More experiments with BartMachine
* Remembering RueLaLa and their forecasting engine.

**Notes**: **---Night at a rooftop, Work and Exploring NY---**


### Day 26: August 11, 2018 (Saturday)

**Activity**: 
* 80000 hours podcast: how should you change the beliefs when encountering new evidence
* SanDiego Fundamentals of Machine Learning week two: Programming assignments and Quizzez


**---Long flight to Bucharest and Moving Out----**

### Day 27: August 15, 2018 (Wednesday)

**Activity**: 
* CASI Chapter 8 on GLM and Regression trees
* CASI Chapter 9 on Survival Analysis (Kaplan-Meier, Log-Rank, CoxPH)
* Presentation on OpenAI Deep reinforcement learning 5v5 Dota 2
* Bayesian Hierarchical models in PyMC3 vs PySTAN
* Light presentation of hierarchical models

**Notes**: PyMC3 is very nice for rapid prototyping and STAN would be better suitable for production systems. Indexing e.g. vectors of parameters might be more tricky in STAN where you have to iterate. For R STAN is the heavy favorite.

### Day 28: August 16, 2018 (Thursday)

**Activity**: 
* Advanced Python: Django Setup, The ORM Model and Framework logic and purpose
* CASI Chapter 10 on Jackknife and Bootstrap

**Notes**: For the Advanced Python, Implement a recommendation system. It's a good chance to practice the python recommendation libraries and prepare for the final exam.

### Day 29: August 17, 2018 (Friday)

**Activity**: 
* A refresher on Clustering, kNN and Distance Measures
* Make a plan for Fast.ai courses
* Prepare the software for the Data Science Summer School

**Notes**: 

### Day 30: August 18, 2018 (Saturday)

**Activity**: 
* CASI Chapter 11 on Bootstrap Distribution
* Fast.ai Computational Linear Algebra Week One
* Fast.ai CLA Week One exercises and programming
* Fast Image processing using Halide
* Record presentation: Data Science and Machine Learning, an interdisciplinary approach to solving complex problems

**Notes**: Fast.ai as a top choice (besides open.ai) for Deep Learning Courses

### Day 31: August 19, 2018 (Sunday)

**Activity**: 
* Review of Washington's Regression Course: Gradient Descent, Ridge, Lasso
* Fast.ai Deep Learning for Coders Week 1
* Fast.ai Deep Learning for Coders Week 2
* List of courses and books for the next year from three perspectives: Deep Learning, Statistical Learning and Bayesian Statistics/Econometrics.

**Notes**: Learn Pytorch for complex cutting-edge ML/Probabilistic algorithms and Tensorflow for simpler, but scalable, production code. Make use of fast.ai's Python library which implements best practices sometimes lost in particular papers (like Restarting Minibatch Gradient Descent, learning rate optimization, data augmentation and so on ...)

### Day 32: August 20, 2018 (Monday)

**Activity**:
* Fast.ai Deep Learning for Coders Week 3
* Fast.ai Computational Linear Algebra Week 2

**Notes**:
1. [distill.pub](distill.pub) for getting high-quality intuitive feel for deep learning model
2. Time Series analysis: FA18 on edx and Novosibirsk course on openedu
3. EdX SanDiego Statistics and Probability for Data Science in Python
4. [neuralnetworksanddeeplearning,com](neuralnetworksanddeeplearning,com) and Ian Goodfellow's free textbook
5. Francois Husson - Multidimensional Exploratory Data Analysis
6. Review once again Yaser Abu-Mostafa's Learning from Data
7. Finish coding from Richard McElreath's Statistical Rethinking
8. Applied Hierarchical Regression Modeling by Jenniffer Hill and Andrew Gelman using STAN instead of JAGS
9. Using R for Introduction to Econometrics, combined with insights from Brian Caffo's Mathematical Biostatistics bootcamp in R
10. Arthur Carpentier's Classification from Scratch series
11. EdX Columbia University Machine Learning
12. EdX SanDiego Fundametals of Machine Learning
13. Fast.ai Deep Learning for Coders
14. Fast.ai Cutting Edge Deep Learning
15. Fast.ai Computational Linear Algebra
16. Andrew NG Open.AI's Deep Learning 1,2,3,4,5
17. Hinton's Neural Networks for Machine Learning
18. MIT AI Support Vector Machines and Boosting Lectures
19. Stanford's CS231 on Computer Vision

### Day 33: August 21, 2018 (Tuesday)

**Activity**:
* Fast.ai Deep Learning for Coders Week 4
* On type I and II errors visualization

### Day 34: August 22, 2018 (Wednesday)
**Activity**:
* Experiments with Survival Random Forests
* Classification on Imbalanced data
* Lift analysis

### Day 35: August 23, 2018 (Thursday)
**Activity**:
* Survival analysis with Cox Proportional hazards for Churn
* Desigh experiment after Ascarza's Futility of Retention
* Introduction to Weibull Time to Event RNNs (Thesis)
* Collect papers for ML approaches to Survival Analysis

**--Travel to Data Science Summer School in Predeal---**
* First half of Fast.ai Deep Learning for Coders Lesson 5

### Day 36: August 24, 2018 (Friday)
**Activity**:
* Fundamentals of Data Science with Dan Nicolae
* A crash course in Statistics by Dan Nicolae
* Dumitru Roman's Data Driven Products at SINTEF
* Second half of Fast.ai Deep Learning for Coders Lesson 5

### Day 37: August 25, 2018 (Saturday)
**Activity**:
* Data Science with Python
* Hands on Statistics with R by Dan Nicolae
* James Hodson's AI for good foundation projects
* First half of Fast.ai Deep Learning for Coders Lesson 6

### Day 38: August 26, 2018 (Sunday)
**Activity**:
* Introduction to machine Learning by Razvan Bunescu
* Deep Learning with Neural Networks workshop by Razvan Bunescu
* Marko Grobelnik's research on knowledge graphs and text understanding


### Day 40: August 27, 2018 (Monday)
**Activity**:
* Hands on workshop on machine learning by Razvan Bunescu
* Introduction to text mining by Marko Grobelnik
* Razvan Bunescu's research on Music and Insulin level predictions, Deep Learning and RNNs


### Day 41: August 28, 2018 (Tuesday)
**Activity**:
* Machine Learning in Finance by James Hodson
* Stop using word2vec article by StitchFix algorithmics

**Notes**: Hiking in Mountains and Barbecue evening


### Day 42: August 29, 2018 (Wednesday)
**Activity**:
* Active Learning articles with Python
* Marko Grobelnik's Demo on Text Mining and Knowledge Graphs
* Data Management: from SQL to Graph Databases and NoSQL
* Dan Nicolae's research on Asthma and Genomics


### Day 43: August 30, 2018 (Thursday)
**Activity**:
* Carlos iglesias on Data Visualization Principles and Frameworks
* Hands on with Neo4j databases with Dumitru Roman
* Hands on Data Visualization Pandas, Matplotlib, Seaborn and scikit-learn with Carlos Iglesias
* Ioan Toma and Chatbots 
* Team project on Bike Sharing Demand Prediction
* Search for potential Datasets on Kaggle and Irvine (Rossmann, Retail, Bike Sharing, Climate, Electricity Demand by Peter Laurinec)
* Linear Regression on Daily Data with STL decomposition. Trend interpolation with Gaussian Processes



### Day 44: August 31, 2018 (Friday)
**Activity**:
* Seasonal Arima for Daily Predictions 
* Quasi-Poisson GLM on hourly data
* Data Preprocessing for Deep Learning with Embeddings for Modeling Seasonality
* Project presentation
* Carlos Iglesias on his project at Madrid's Politechnical University

**---End of Data Science Summer School in Predeal---**

### Day 45: September 1, 2018 (Saturday)
**Activity**
* Predicting Customer Lifetime Value with Embeddings paper
* On youtube recommendation algorithms
* Feedback for the summer school


### Day 46: September 2, 2018 (Sunday)
**Activity**:
* Bayesian Statistics with RJags Course on datacamp
* Numberophile on Dollar Game
