# Linear-Discriminant-Analysis-LDA-
## Implementing Machine Learning Algorithm : Linear Discriminant Analysis (LDA) on the data-set of Different Flavors of Vines
Linear Discriminant Analysis (LDA) is a dimensionality reduction technique. As the name implies dimensionality reduction techniques reduce the number of dimensions (i.e. variables) in a dataset while retaining as much information as possible. For instance, suppose that we plotted the relationship between two variables where each color represent a different class

### Linear Discriminant Analysis can be broken up into the following steps:

Compute the within class and between class scatter matrices

Compute the eigenvectors and corresponding eigenvalues for the scatter matrices

Sort the eigenvalues and select the top k

Create a new matrix containing eigenvectors that map to the k eigenvalues

Obtain the new features (i.e. LDA components) by taking the dot product of the data and the matrix from step 4
