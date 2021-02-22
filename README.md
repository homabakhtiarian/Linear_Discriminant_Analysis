# Linear Discriminant Analysis (LDA)

LDA is commonly used as a dimensionality reduction technique.
It's used in the pre-processing step for pattern classification in machine learning algorithms.
And its goal is to project a data set onto a lower dimensional space.
Sounds similar to PCA, but LDA differs because in addition to finding the component axes with LDA we
are interested in the axes that maximize the separation between multiple classes.

To break it down further, the goal of LDA is to project a feature space onto a small subspace while maintaining the class discriminatory information.
And we have both PCA and LDA as linear transformation techniques used for dimensionality reduction. PCA
is a unsupervised algorithm but LDA is supervised because of the relation to the dependent variable.


The five main steps for LDA include the following.
The computation of the D dimensional mean vectors, the computation of the scatter matrices, you have to
also compute the eigenvectors, sort the eigenvectors by decreasing eigenvalues and use the D * K
eigenvector matrix to transform the samples onto the new subspace. overall very similar to PCA.

But the main distinction with LDA to take away is that we're looking for that class separation within the data.
Overall if you're coming from PCA this should seem familiar for the majority of operations if you're
new to this I advise you to go take a look at PCA as well.

