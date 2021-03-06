# Semi Supervised Classification With Cluster Ensembles
## Abstract
We propose a method for semi-supervised classification using a combination of ensemble clustering and kernelbased learning. The method works in two steps. In the first step, a number of variants of clustering partition are obtained with some clustering algorithm working on both labeled and unlabeled data. Weighted averaged co-association matrix is calculated using the results of partitioning. We prove that this matrix satisfies Mercer’s condition, i.e., it defines symmetric non-negative definite kernel. In the second step, a decision function is constructed on labeled data using the obtained matrix as kernel. Some theoretical properties of the proposed method related to its convergence to the optimal classifier are investigated. Numerical experiments show that the proposed method possesses accuracy comparable with some state of the art methods, and in many cases outperforms them. We will illustrate the performance of the method on the problems of semi-supervised classification of
hyperspectral images.


[Data Clustering Using Evidence Accumulation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.2.3429&rep=rep1&type=pdf): Authored by Anil Kumar Jain and Ana L.N. Fred. The paper describes algorithms for creating co-association matrix
