- Feature transformation function is used to make the data linearly separable 
    => Model is not trained on Data D but on transformation of Data phi(D).

- finding a good feature transformation whihc actually makes the data linearly separable has to be done by hand
- you usually try out polinominal feature transformations first
- feature transformation transforms data to a higher dimensional space 
- You have the original Data and the Kernel Matrix. The kernel matrix is given by the feature transformatotion function you want to use. By multiplying the kernel matrix and the original Data you get the transformed data on which you apply the regression. 

i) Wende die kernelfunktion auf X^T und x^' an.  