# *coterie (n)*:  an intimate and often exclusive group of persons with a unifying common interest or purpose

This goal of this project is to identify novel statistical methods of identifying groupwise associated object sets ("coteries") in high-dimensional data.

We aim to:
* Implement or re-implement published methods into complete R packages
* Construct a wrapper package, `coterie`, that standardizes the analysis process for community detection.
* Create a rich tutorial series for implementation of `coterie` algorithms in biomedical context
* Establish a web application for batch data processing via `coterie` algorithms.


# Methods to implement/wrap

## Variable-to-set testing

The following methods rely on variable-to-set group association testing.

* = Permission has been granted by the code authors to re-implement existing code into a shared package.


#### Extraction of Statistically Significant Clusters

[Annals of Applied Statistics paper](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-8/issue-3/A-testing-based-extraction-algorithm-for-identifying-significant-communities-in/10.1214/14-AOAS760.full)

#### Differential Correlation Mining*

[Annals of Applied Statistics paper](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-12/issue-2/A-testing-based-approach-to-the-discovery-of-differentially-correlated/10.1214/17-AOAS1083.short)

#### Latent Association Mining in Binary Data*

[Arxiv paper](https://arxiv.org/abs/1711.10427)

#### Continuous Configuration Model Extraction*

[Journal of Machine Learning Research Paper](https://www.jmlr.org/papers/volume18/17-377/17-377.pdf)

## Other Resources

*Overview of Other Methods:* [A Comparative Analysis of Community Detection Algorithms on Artificial Networks](https://www.nature.com/articles/srep30750)

*API model:* [igraph implementation of network clustering methods](https://github.com/igraph/rigraph/blob/dev/R/community.R)
