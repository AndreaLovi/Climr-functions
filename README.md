# Climr-functions
1)a new method for the class “climr” called gp_fit. This function takes in input the class object and a string argument, which should be one of c(“Nelder-Mead”, “BFGS”, “SANN”, “Brent”). This method apply a Gaussian process with a selected optimization mode to generic datasets. 
2) A plot method for the class climr_gp_fit. Similarly to the plot method for a climr_fit object, this method will use ggplot2 to illustrate the data as a scatterplot, and will add the smoothed Guassian process regression line.
