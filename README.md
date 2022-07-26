# DataMining-FirstPart

Group members:
- [Ismaele Gorgoglione](https://github.com/noysma)
- [Federica Altavilla](https://github.com/federicaaltavilla)
- [Aura Petrucci](https://github.com/aurapetrucci)
- [Salvatore Giovino](https://github.com/SalvoGiovi)

## Data Understanding & Preparation
-	Data Semantics
    -	Introduce the variables with their meaning and characteristics;
-	Distribution of the variables and statistics
    -	Explore (single, pairs of…) variables quantitatively (e.g., statistics, distributions);
-	Assessing data quality
    -	Are present errors, outliers, missing values, semantic inconsistencies, etc?
-	Variable transformations
    -	Is it better to use for further modules transformed variables (e.g., log-transformated)?
-	Pairwise correlations and eventual elimination of variables
    -	Matrix correlation (analyze high correlated variables);

## Clustering
-	Clustering analysis by K-Means
    -	Choice the attributes, identify the best value of k, characterize the clusters (w.r.t. centroid analysis and variable distribution within);
-	Analysis by density-based clustering
    -	Choice the attributes, identify the best parameter configuration, characterize clusters;
-	Analysis by hierarchical clustering
    -	Choice the attributes, the distance function, analyze several dendrograms;
-	Final discussion
    -	Which is the best algorithm? Remember that best is studied w.r.t. several aggregate statistics, cluster distributions and w.r.t. the typology of algorithm used for that particular dataset;

## Classification
-	Classification by Decision Trees
    -	Choice the attributes, identify the best parameter configuration(s), eg. gain criterion, then visualize, interpret the tree(s).
    -	Evaluate the performances of the algorithm(s) w.r.t. confusion matrix, accuracy, precision, recall, F1, ROC curve.
-	Classification by Other Algorithms or Baselines
    -	Try to use another classification algorithm (KNN or Random Forest, suggested) or use a baseline model for the comparison.
-	Final discussion
    -	Which is the best algorithm? Best can be studied w.r.t. the performance evaluation or other preferred point of view.

## Pattern Mining
-	Frequent Pattern extraction
    -	Using different values of support, etc.
-	Discuss Frequent Pattern
    -	Including qualitative and quantitative analysis, e.g., how the number of patterns w.r.t k min_sup changes.
-	Association Rules extraction
    -	Using different values of confidence, etc.
-	Discuss Association rules
    -	Including qualitative and quantitative analysis, e.g., how the number of rules w.r.t k min_conf changes, histograms of rules’ confidence and lift.
-	Exploit the most useful extracted rules
    -	E.g., use them to replace missing values or to predict the target variable.
