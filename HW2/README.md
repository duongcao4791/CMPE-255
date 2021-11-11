# CMPE-255 Assignment 2

Colab link https://colab.research.google.com/drive/14rNxbv80_WpIK2YrbVcow2mDPi2eP1BK?usp=sharing

Conclusion

PCA is far and away the fastest option. 

SVD there’s generally no benefit for using SVD over PCA for dimensionality reduction. PCA 

LLE there is only one parameter to tune, which is the value of K, or the number of nearest neighbours to consider as part of a cluster. It may sometimes perform better than PCA, and sometimes worse.

UMAP works well for high dimensional data, it's the next best option in terms of performance among the implementations. Its run-time is shorter as compared to t-SNE.

ISOMAP: We use this technique when the data is strongly non-linear

t-SNE: This technique also works well when the data is strongly non-linear. It works extremely well for visualizations as well


