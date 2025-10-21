* TITLE: DS 290: Modelling and Simulation
* AUTHOR: Piyush Kumar

This repository contains lecture notes and summaries for *DS 290: Modelling and Simulation (August 2025)*, based on the book *Discrete-Event System Simulation* by Jerry Banks, Carson, Nelson & Nicol.

* 📘 Topics Covered

*** Statistical Models
- Discrete & continuous random variables
- Common distributions: Exponential, Normal, Gamma, Weibull, Poisson
- Applications: Queueing, Inventory, Reliability
- Empirical distributions

*** Queueing Models
- Components: server, customer, arrival, queue discipline
- Markovian queues, multiserver queues
- Performance metrics: utilization, delay
- \( L = \lambda W \) formula

** Random Number & Variate Generation
- Linear Congruential Method (LCM)
- Acceptance-Rejection technique
- Inverse transform
- Thinning method for NSPP

** Input Modeling
- Histogram, Q-Q plot
- Goodness-of-fit: Chi-square, K-S Test
- Parameter estimation (MLE)
- Fitting Non-Stationary Poisson Process

** Conditional Expectation
- Partition theorem
- Conditional PDF: \( f_{X|Y}(x|y) = \frac{f_{X,Y}(x,y)}{f_Y(y)} \)

** Simulation Output Analysis
- Terminating vs. steady-state
- Confidence & prediction intervals
- Initialization bias
- Estimating required number of replications

** Validation & Verification
- Trace, debugging
- Model calibration
- Type I & II errors
- Turing test, historical validation

** Comparison of System Designs
- Independent vs. correlated sampling (CRN)
- Confidence interval comparisons
- Bonferroni correction
- Metamodels: regression, heuristics

* 🧪 Mid & End Sem Schedule
- [X] Mid Sem 1: Chapters 5–8 (17 Sep) – 25%
- [x] Mid Sem 2: Chapters 9–12 (15 Oct) – 25%
- [ ] End Sem: Full Syllabus (24 Nov) – 50%

* 📝 Glossary
- i.i.d. = independent and identically distributed
- FIFO = First In First Out
- TTF = Time to Failure
- NSPP = Non-Stationary Poisson Process
