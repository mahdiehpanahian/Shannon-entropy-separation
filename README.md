# Classified the Iris dataset with A New Techniques Based on Shannon Entropy

#### The purpose is to use Shannon entropy measures to develop classification techniques and an index which estimates the separation of the groups in a finite mixture model. These measures can be applied to machine learning techniques such as discriminant analysis, cluster analysis, exploratory data analysis, etc. If we know the number of groups and we have training samples from each group (supervised learning) the index is used to measure the separation of the groups. Here some entropy measures are used to classify new individuals in one of these groups. If we are not sure about the number of groups (unsupervised learning), the index can be used to determine the optimal number of groups from an entropy (information/uncertainty) criterion. It can also be used to determine the best variables in order to separate the groups. In all the cases we assume that we have absolutely continuous random variables and we use the Shannon entropy based on the probability density function. Theoretical, parametric and non-parametric techniques are proposed to get approximations of these entropy measures in practice.

## How it works?
- assume a Normal (Gaussian) distribution for these data in each group. As we know that there are three groups.
- estimate the means and variance-covariance matrices in each group (by using only the data in each group).
- use them to estimate the PDF fi in each group by using normal PDF with these parameter values. The estimations of the respective PDF are represented by fi for i =1, 2, 3.
- approximate the entropies in the groups for the multivariate case.

## Screenshots

![image](https://github.com/mahdiehpanahian/Shannon-entropy-separation/assets/123892361/9fa5f479-32a8-41ed-b201-e494d2ea0806)

![image](https://github.com/mahdiehpanahian/Shannon-entropy-separation/assets/123892361/84ec0f29-5507-48d5-b093-f8b0bd67f284)
