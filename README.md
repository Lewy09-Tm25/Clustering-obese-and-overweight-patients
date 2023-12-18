# Clustering-obese-and-overweight-patients

The Clustering Using Representatives algorithm is a large-scale clustering method that obeys the point-assignment approach of algorithms. Unlike some approaches that assume normally distributed clusters in an Euclidean space, CURE doesn't have a pre-defined assumption regarding the shapes of the clusters. They can exhibit irregular shapes like bends, S-shapes, or rings. Rather than relying on centroids, CURE represents clusters using a set of representative points, allowing for greater flexibility in capturing diverse cluster shapes and structures.\

To understand the algorithm practically, this project has been implemented.

### Dataset
The dataset, comprising 2111 records, was amassed using a web-based survey platform where anonymous respondents provided information on the 17 attributes. The task involves clustering individuals into distinct categories considering their varied eating habits, physical conditions, age, gender, and vital metrics like height and weight. For this analysis, only six attributes—Gender, Age, Height, Weight, family\_history\_with\_overweight, and the target variable NObeyesdad—were selected.

To understand the performance of The CURE algorithm and compare it with other hierarchical clustering algorithms, this dataset\cite{dataset} was used to cluster individuals based on their biographic facts. The target column shows the status of the person.

### File structure
- **Obesity.ipynb** - contains the evaluation and comparison with other hierarchical clustering methods
- **model selection.ipynb** - contains the hyperparameter tuning of the CURE algorithm to select the best possible parameters for model evaluation
- **ObesityDataSet.csv** - source dataset for the project. Cite - https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster
