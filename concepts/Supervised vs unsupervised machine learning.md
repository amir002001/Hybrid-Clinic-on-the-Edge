# Supervised vs unsupervised machine learning

Date: 2022-04-02

## Description
https://www.ibm.com/cloud/blog/supervised-vs-unsupervised-learning
### What is supervised learning?
Supervised learning is a machine learning approach that’s defined by its use of labeled datasets. These datasets are designed to train or “supervise” algorithms into classifying data or predicting outcomes accurately. Using labeled inputs and outputs, the model can measure its accuracy and learn over time.

Supervised learning can be separated into **two types of problems** when **[[data mining]]**: classification and regression:

* **[[Classification]]** problems use an algorithm to **accurately assign test data** into **specific categories**, such as *separating apples from oranges*. Or, in the real world, supervised learning algorithms can be used to classify spam in a separate folder from your inbox. Linear classifiers, support vector machines ([[Support Vector Machine]], [[decision trees]] and [[random forest]] are all common types of classification algorithms.
* **[[Regression Analysis]]** is another type of supervised learning method that uses an algorithm to understand the relationship between dependent and independent variables. Regression models are helpful for **predicting numerical values** **based on different data points**, such as sales *revenue projections* for a given business. Some popular regression algorithms are [[linear regression]], [[logistic regression]] and [[polynomial regression]].

### What is unsupervised learning?

[Unsupervised learning](https://www.ibm.com/cloud/learn/unsupervised-learning) uses machine learning algorithms to *analyze and cluster **unlabeled data sets***. These algorithms *discover hidden patterns* in data **without the need for human intervention** (hence, they are “*unsupervised*”).

Unsupervised learning models are used for three main tasks: clustering, association and dimensionality reduction:

-   **Clustering** is a [[data mining]] technique for *grouping unlabeled data* based on their *similarities or differences*. For example, K-means clustering algorithms assign similar data points into groups, where the K value represents the size of the grouping and granularity. This technique is helpful for *market segmentation*, *image compression*, etc.
-   **Association** is another type of unsupervised learning method that uses different rules to *find relationships between variables* in a given dataset. These methods are frequently used for *market basket analysis* and *recommendation engines*, along the lines of “Customers Who Bought This Item Also Bought” recommendations.
-   **Dimensionality reduction** is a learning technique used when the number of features  (or dimensions) in a given dataset is too high. It *reduces the number of data inputs* to a manageable size while also preserving the data integrity. Often, this technique is used in the preprocessing data stage, such as when autoencoders remove noise from visual data to improve picture quality.

## Tags


## Related Topics