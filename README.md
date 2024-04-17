# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2024

+ Team #7
+ Project title: Machine Learning Fairness
+ Team members
	+ Kechen Lu
	+ Siyu Li 
	+ Fei Li
+ Project summary: In this project, we implement two algorithms: Information Theoretic Measures for Fairness-aware Feature selection and Learning fair representations (LFR) on the compas-two-years dataset. We used an information theoretic approach to feature selection with the aim of reducing bias in the COMPAS recidivism dataset focused on Caucasian and African-American defendants. We utilized Shapley value analysis to understand the contribution of each feature to both prediction accuracy and fairness. After identifying and removing features that contributed to bias, such as 'Age', we trained a logistic regression model. The revised model showed a slight decrease in accuracy but improved in fairness, indicating the effectiveness of our feature selection method in creating a more equitable predictive model.
	
**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
