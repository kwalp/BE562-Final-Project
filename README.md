## ENG BE 562: Computational Biology: Machine Learning Fundamentals
# Bayesian Networking for Prediction of Breast Cancer Survival Based on Transcriptomic Data

### By: Isha Mukundan, Kara Walp, and Sofia Polychroniadou

Dataset:
Breast Cancer Gene Expression Profiles (METABRIC): 
https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric

Abstract:
This study investigates the application of Bayesian Networks (BNs) to predict breast cancer survival outcomes using gene expression and mutation data from the METABRIC dataset. While traditional prognostic tools like the Breast Cancer Index Test analyze a limited number of genes, this project leverages modern genomic technologies to develop a more comprehensive predictive model. We implemented a mixed-distribution Bayesian network incorporating gaussian gene expression nodes, binomial gene mutation nodes, and a Bernoulli survival outcome node. The network topology was learned using a hill climbing algorithm with Bayesian Information Criterion optimization, and parameters were estimated through Maximum Likelihood Estimation. Model validation through 5-fold cross-validation yielded an average Area Under Curve (AUC) score of 0.53, falling short of the target 0.7 threshold. Comparative analysis with existing literature revealed that this performance aligns with other machine learning approaches using this dataset, suggesting that these specific gene expression profiles alone may not be sufficient predictors of breast cancer survival. Our findings indicate that while the Bayesian Network effectively captured available genetic relationships, the fundamental predictive power of gene expression data for survival outcomes may be inherently limited, highlighting the potential need to integrate clinical variables for more accurate prognostic modeling.
