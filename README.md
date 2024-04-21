This project performs co-clustering for pollution and weather variables for the South Region of France. 
We first read in our data, reshaped it into five arrays representing the five variables, Nitrogen dioxide, Particulate matter, Ozone, Temperature and Pressure. 
We performed co-clustering separately for the arrays and also did for the multivariate functional data comparing our results with that of the original article. 
Then we performed multifunctional principal component analysis to retrieve the principal components and performed co-clustering on the expansion of the bases using the scores from the principal components to create our adjacency matrix and specifying Latent Block Model as the membership type for the nodes.
