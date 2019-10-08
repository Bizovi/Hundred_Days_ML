# Hundred days of (not only) Machine Learning

An important part of learning and trying to be on top of latest developments is
 being consistent, keeping track of papers, books, notes and code. After
 filling the shelves with handwritten notes, I needed a better way to manage
 the content. This repository has two components:

* A chronological timeline of papers and books read, conferences attended and
 experiments done.
* A [wiki](https://github.com/Bizovi/Hundred_Days_ML/wiki) with a curated
 list of resources by topic, with links to my code (when appropriate) or
 other repositories.
* The content from last year will be in `archive/` and gradually revised for
 the curated list.


### September 28, 2019 (Saturday)
* Yanis Varoufakis - [Talking to my daughter about the economy](https://www.amazon.co.uk/Talking-Daughter-About-Economy-Capitalism/dp/1847924441): A brief
 history of capitalism
* Kent Beck - [Test-Driven Development](https://www.amazon.co.uk/Test-Driven-Development-Addison-Wesley-Signature/dp/0321146530/ref=sr_1_1?crid=8TA4GZ66UV7W&keywords=test+driven+development&qid=1569760735&s=books&sprefix=test+driven%2Cstripbooks%2C176&sr=1-1) by example

*"Talking to my daughter about the economy"* makes for delightful three hours
 of reading, but don't underestimate this book in terms of **impact** and its
 *implicit* references to the following topics, which I'm going to interpret in
 my own way:

* Joseph Stiglitz - [The Price of Inequality](https://www.amazon.com/Price-Inequality-Divided-Society-Endangers-ebook/dp/B007MKCQ30/ref=sr_1_1?crid=RY9R0J7Z3OXP&keywords=stiglitz+inequality&qid=1569762899&s=gateway&sprefix=stiglitz+ine%2Caps%2C249&sr=8-1):
How Today's Divided Society Endangers Our Future. I would recommend Stiglitz
over Piketti on this topic, but that's just me.
* Francis Fukuyama - [The origins of political order](https://www.amazon.com/s?k=fukuyama+origins+of+political+order&crid=3E7E0HPDGZMEO&sprefix=fukuyama+origin%2Caps%2C249&ref=nb_sb_ss_i_1_15),
[Political order and political decay](https://www.amazon.com/Political-Order-Decay-Industrial-Globalization/dp/0374535620/ref=sr_1_2?crid=Z7TBID6YIOMK&keywords=fukuyama+political+order&qid=1569763203&s=gateway&sprefix=fukuyama+politica%2Caps%2C-1&sr=8-2).
A comparative analysis on the emergence of states, rule of law, democratic
 accountability and political decay. Their interplay is an important topic in
 order to better understand the economic context.
* Great Britain's transition from a society with markets to a society of
markets, with an accent on labor. Experiential value in contrast with exchange
 value.
* [Minsky's](https://www.amazon.com/Stabilizing-Unstable-Economy-Hyman-Minsky/dp/0071592997/ref=sr_1_3?keywords=minsky&qid=1569763645&s=gateway&sr=8-3) idea of inherent instability, the dynamics of debt and profits
, money, deflation, employment. The [Goodwin-Lotka-Volterra](https://www.systemdynamics.org/assets/conferences/2005/proceed/papers/WEBER196.pdf) model is an
 elegant mathematical representation of this idea.
* (Common) expectations, markets and self-fulfilling prophecies. How a WWII
 [prisoner camp market](http://homepage.ntu.edu.tw/~yitingli/file/Money%20and%20Banking/The%20Economic%20Organisation%20of%20a%20P.O.W.%20Camp.pdf) differs from the real world.
* [The economics of money and banking](https://www.coursera.org/learn/money-banking),
the political nature of money ([Where does money come from?](https://www.amazon.com/Where-Does-Money-Come-Ryan-Collins/dp/1521043892/ref=sr_1_1?keywords=where+does+money+come+from&qid=1569763978&s=gateway&sr=8-1)).
* Elinor Ostrom - [Governing the Commons: The Evolution of Institutions for Collective Action](https://www.amazon.com/Governing-Commons-Evolution-Institutions-Collective/dp/1107569788/ref=sr_1_1?keywords=elinor+ostrom&qid=1569764070&s=gateway&sr=8-1)
and the "Tragedy of the commons".

**Other important works by Y. Varoufakis:** The list below is the books read
, although "And the Weak Suffer What They Must?", "The global minotaur" also
 deserve attention.

* [Economic Indeterminacy](https://www.amazon.com/Economic-Indeterminacy-encounter-economists-Routledge-ebook/dp/B00FQGQH9G/ref=sr_1_1?keywords=economic+indeterminacy&qid=1569762217&s=gateway&sr=8-1):
A personal encounter with the economists' peculiar nemesis
* [Adults In the Room](https://www.amazon.com/Adults-Room-European-American-Establishment/dp/0374538050/ref=sr_1_1?crid=3MQOW45ATP1AE&keywords=adults+in+the+room&qid=1569762306&s=gateway&sprefix=adults+in+the+room%2Caps%2C248&sr=8-1): My Battle with the European and American Deep
 Establishment
* [Game Theory](https://www.amazon.com/Game-Theory-Shaun-Hargreaves-Heap/dp/0415094038/ref=sr_1_1?keywords=game+theory+varoufakis&qid=1569762342&s=gateway&sr=8-1):
A critical introduction


### September 29, 2019 (Sunday)

* Jurgen Appelo - [Management 3.0](https://www.amazon.com/Management-3-0-Developers-Developing-Addison-Wesley/dp/0321712471/ref=sr_1_1?keywords=agile+management+3.0&qid=1569764229&s=gateway&sr=8-1):
Leading Agile Developers, Developing Agile Leaders **[Chapters 1-5]**

Me, as other people who were drawn to this book absolutely hate cookbook-style
management books, for a good reason, especially if coming from a scientific
 background. Jurgen draws sound connections between the complexity theory and
  self-organizing teams, providing an invaluable counterpart to the numerous
  materials on Agile software development.


> Watched (some of) the [recordings](https://www.youtube.com/playlist?list=PL4IzsxWztPdliwImi5JLBC4BrvqxG-vcA) of **UseR! Conference** (Toulouse, 2019) and here are some of the most interesting highlights I found so far, worth checking out *(on forecasting and time series)*:

* **I. Svetunkov - Smooth forecasting in R** (some cutting-edge state-space models for fast-moving, slow-moving, and multivariate time series)
* **T. Talagala, R.Hyndman** - Feature-based time series forecasting. An **amazing idea** of predicting the best model/error based on the features of time series, acknowledging the concept of no free lunch. Also has an associated R package: `ffmorpp`.
* Forecast combination talk by Eran Raviv
* Time series packages in R by M. O'Hara, R. Hyndman: `tsibble, feasts, tsibbledata, fable` as a part of `tidyverts.org` ecosystem which is meant to replace the outdated base R  system of ts + forecast/fpp2. Chrispoh Sax's `tsbox` also deserves attention, as an "adapter" between different time series formats.


### September 30, 2019 (Monday)
* Implemented an **Inventory Forecasting** API in Flask, which takes into account a demand forecast, current in inventory, purchase orders, and adjustments to the latter two.
* An amazing presentation on ["Safe Handling Instructions for Probabilistic Classification"](https://www.youtube.com/watch?v=RXMu96RJj_s&list=PLYx7XA2nY5GcDQblpQ_M1V3PQPoLWiDAC&index=12) by Gordon Chen (SciPy, 2019), about the rarely discussed, but extremely important topic of calibrating probabilistic classification models.
    * Would have saved me from a lot of pain when I was working on churn and propensity models, where calibrated probabilities are essential for designing good retention programs.
    * Should be a mandatory watch after any course on ML/Classification!
* I. Svetunkov - [Old dog, new tricks](https://www.researchgate.net/publication/320130719_Old_dog_new_tricks_a_modelling_view_of_simple_moving_averages): a modeling view of simple moving averages. An amazing paper which sheds a new light on a basic, but underrated method and serves as an excellent introduction / entry point to the theory behind `smooth` package (of state-space models).


### October 1-4, 2019 (Tuesday-Friday)
**Some Work:**
* Deployed the **Inventory Forecasting** API in Cloud Run and Cloud Endpoints. Ran some experiments to see the impact of demand forecasting model choice on resulting inventory at the end of lead time.
* Derived a statistical model for **breaking down a forecast** for lingerie items to the size level (SKUs): stochastic assumptions, causal diagrams, estimators and tests.


**Some Writing:**
* The first part of a new blog post coming soon: **"A five year journey in Data Science"**.
* Research for the blog post: **"A point or two on Simple Moving Average"**, based on I. Svetunkov's paper, but taking the explanation further (going through the reference loophole).
* A **presentation** on statistical models and methods in Procurement, Demand and Inventory Management at Adore Me.

**Some Reading:**
* Aileen Nielsen - [Modern Time Series Analysis](https://www.youtube.com/watch?v=v5ijNXvlC5A) workshop (SciPy, 2019) is a three-hour brilliance, going through Structural/Bayesian time series, Machine Learning methods and their challenges for time series, and Deep Learning architectures.
* Reading the original papers on Temporal Convolutional Neural Networks and recent developments in Probabilistic forecasting with TCNs. Some key concepts are sequence to sequence modeling, 1D causal convolutions and dilating convolutions.
    * Also, architectures as DeepAR (Amazon), WaveNet deserve attention, despite the complexities introduced by their autoregressive nature.


### October 5, 2019 (Saturday)

* Binge-watched **numberophile** videos on Navier-Stokes, Monster Groups, free will, Mandelbrot and Julia sets, Stable Marriage problems, Integer Sequence plots.
* Reviewed a course I went through in 2016: [Supply Chain Fundamentals](https://courses.edx.org/courses/course-v1:MITx+CTL.SC1x+2T2018/course/), (MIT, EdX). **[Week 1-3]** are about supply chain segmentation techniques, **exponential smoothing forecasting**, intermittent demand and new products forecasting.
    * A great course to understand the mechanical details of exponential smoothing and get both a big picture and detailed overview of models and objectives in SCM.
    * The models are not enough for real-world scenarios, but are an amazing starting point to formulate own models.
    * The course uses spreadsheets, but is easily translatable in R/Python code.



### October 6, 2019 (Sunday)
* [System Dynamics and Complexity](https://video.ethz.ch/lectures/d-mtec/2012/autumn/363-0541-00L.html) by F. Schweitzer (2012) (Zurich ETH, Lecture 1). The first lectures is an overview of problem solving, basic concepts and real world challenges in which systems thinking, dynamics and complexity should be an invaluable tool.
* [Analytics in Python](https://courses.edx.org/courses/course-v1:ColumbiaX+BAMM.101x+3T2019/course/) - (Columbia University, EdX) micromasters in Business Analytics. I found the web scraping, text mining and network analysis session to be very useful as practice exercises.
    * Intro to python (first two weeks) can be safely skipped.
    * The **web scraping session is amazing**, deserves some practice.
    * The NLP/Text mining session is a very good overview of **coding aspects** when working with simple methods. For an advanced course, I would look into Fast.AI's "NLP for programmers".
    * The network analyses weeks are good, but another course such as Network Analysis in Python (Michigan, Coursera), gives much more depth. Also, see my [blog post](https://bizovi.github.io/post/networks/) with analyses and visualizations done using same package (`networkx`).
    * The machine learning examples (last two weeks) are rather weak.
* Compiled a list of Zurich's ETH freely available lecture recordings on System Dynamics, Economic Networks, Firm Dynamics, Statistical Learning Theory, Machine and Deep Learning.
* Jurgen Appelo - [Management 3.0](https://www.amazon.com/Management-3-0-Developers-Developing-Addison-Wesley/dp/0321712471/ref=sr_1_1?keywords=agile+management+3.0&qid=1569764229&s=gateway&sr=8-1): Leading Agile Developers, Developing Agile Leaders **[Chapters 6-7]** on Self-Organization and practical aspects of "energizing people" and empowering teams.


### October 7, 2019 (Monday)

* Implemented and deployed an **Inventory Optimization** API in Cloud Run, Endpoints and Flask, which supports different strategies, parameters and combination of strategies.
* Read the first chapter of [General Systems Theory by Ludwig von Bertalanffy](https://monoskop.org/images/7/77/Von_Bertalanffy_Ludwig_General_System_Theory_1968.pdf) as a part of Zurich ETH lectures on System Dynamics and Complexity (2012) assignment.
* An excellent one pager in [nature](https://www.nature.com/articles/427399a.pdf): "Engineering complex systems" by J. Ottino.


### October 8, 2019 (Tuesday)

* John Leeman - A brilliant [workshop](https://www.youtube.com/watch?v=LX2ksGYXJ80&t=3750s) on testing scientific Python code. The course page is [here](https://leemangeophysicalllc.github.io/testing-with-python/). The framework used is `pytest`, which is more friendly for beginners than the built-in `unittest`.
* Please, refer to the original source or my [python repo](https://github.com/Bizovi/Learning-Python/tree/master/python_testing) for the coded solutions.
* Coded an experiment on influence of demand forecasting uncertainty on the state of inventory given a replenishment policy.
* [System Dynamics and Complexity](https://video.ethz.ch/lectures/d-mtec/2012/autumn/363-0541-00L.html) by F. Schweitzer (2012) (Zurich ETH, Lecture 2).
