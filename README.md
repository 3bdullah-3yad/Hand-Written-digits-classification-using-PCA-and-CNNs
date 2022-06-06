# Hand-Written-digits-classification-using-PCA-and-CNNs

**Principal Component Properties**
There are two main properties of principal components:

- They retain the most amount of information in the dataset.
- The created components are orthogonal to one another. When there are many components, the additional components will all be orthogonal to one another. Depending on how the components are used, there are benefits to having orthogonal components. In regression, we often would like independent features, so using these components in regression now guarantees this.



**What Are Eigenvalues and Eigenvectors?**
<br>The mathematics of PCA isn't really necessary for PCA to be useful. However, it can be useful to fully understand the mathematics of a technique to understand how it might be extended to new cases. For this reason, there are few additional references which go more into the mathematics of PCA at the end of this file.

If you dive into the literature surrounding PCA, you will without a doubt run into the language of eigenvalues and eigenvectors. These are just the math for PCA.

An eigenvalue is the same as the amount of variability captured by a principal component, and an eigenvector is a principal component itself. To see more on these ideas, take a look at the following three links below:

[Eigenvalue](https://mathworld.wolfram.com/Eigenvalue.html)

[Eigenvalue and eigenvector](https://www.mathsisfun.com/algebra/eigenvalue.html)

[A great introduction into the mathematics of principal components analysis.](https://drive.google.com/file/d/1b7CXpIIyxIW32LXHQVtoKPq_n5-DieJz/view?usp=sharing)

[An example of using PCA in python by one of my favorite data scientists.](https://sebastianraschka.com/Articles/2015_pca_in_3_steps.html)

[An example of PCA from the scikit learn documentation.](https://scikit-learn.org/stable/auto_examples/applications/plot_face_recognition.html#sphx-glr-auto-examples-applications-plot-face-recognition-py)
