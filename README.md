# framework-comparison
A simple comparison of a few ML frameworks

## Languages and Properties

--------------------------------------------------------------
|=Framework=| Languages | Licence                            |
|-----------|-----------|------------------------------------|
| MLPack    | C++       | BSD                                |
| Shogun    | C++       | Mostly BSD, some parts GPL/nonfree |
| Sklearn   | Python    | BSD                                |

## Metrics

-------------------------------------------------------------------------------------
|=Framework=| L-Norms     | Mahlanobis | KL Divergence | Cosine | Hamming | Jaccard |
|-----------|-------------|------------|---------------|--------|---------|---------|
| MLPack    | Yes         | Yes        | Yes           | Yes    | No      | No      |

## Clustering

----------------------------------------------------------------------------------------
|=Framework=| KMeans             | Hierarchical | Spectral | DBSCAN | Mean-shift | GMM |
| MLPack    | Yes, with KMeans++ |              |          | Yes    | Yes        | Yes |

## Classification

---------------------------------------------------------------------------------------------------------------------
|=Framework=| Decision Tree      | Logistic Regression | Adaboost | Perceptron | Random Forest | Softmax Regression |
|-----------|--------------------|---------------------|----------|------------|---------------|--------------------|
| MLPack    | Yes                | Yes                 | Yes      | Yes        | Yes           | Yes                |

## Regression

-------------------------------------------------------------------
|=Framework=| Linear             | Perceptron          | LASSO    |
|-----------|--------------------|---------------------|----------|
| MLPack    | Yes                | Yes                 | Yes      |

## Dimensionality Reduction

----------------------------------------------------------
|=Framework=| PCA | Kernel PCA | LDA | Random Projection |
|-----------|-----|------------|-----|-------------------|
| MLPack    | Yes | Yes        | No  | No                |

## Kernel Methods

-----------------------------------------------------------------------------------------------------
|=Framework=| Cosine | Epanechnikov | Gaussian | Tanh | Laplacian | Linear | Polynomial | Spherical |
|-----------|--------|--------------|----------|------|-----------|--------|------------|-----------|
| MLPack    | Yes    | Yes          | Yes      | Yes  | Yes       | Yes    | Yes        | Yes       |

## Probabilistic Methods

## Ensembling

## Cross-Validation

-----------------------------------------------------------------------------------------------------
|=Framework=| KFold  | Epanechnikov | Gaussian | Tanh | Laplacian | Linear | Polynomial | Spherical |
|-----------|--------|--------------|----------|------|-----------|--------|------------|-----------|
| MLPack    | Yes    | Yes          | Yes      | Yes  | Yes       | Yes    | Yes        | Yes       |

## Hyperparameter Search

## Algorithms
