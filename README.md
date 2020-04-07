# Online-convex-optimization

Implementation of different online convex optimizabation algorithms, based on the book of [E. Hazan, 2019](https://ocobook.cs.princeton.edu/OCObook.pdf). We test these algorithms for the problem of learning a linear SVM with MNIST dataset. For simplification, we resctrict the problem of binary classification (0 or other). Our criterion for comparaisons is the test score, expressed as a loss.
In particular, we use some functions for all algorithms : 

- *hingereg*, return regularized hinge loss
- *gradreg*, which return the gradient of the regularized hinge loss
- *hinge_reg_sgd* and *grad_reg_sgd*, same functions for stochastic case

Algorithms we use are : Gradient descent (projected or not), Stochastic gradient descent (projected or not), Adagrad, Exponentiated gradient, Online Newton Step, Stochastic mirror descent, Online Smooth Projection Free and Sampled Follow the Perturbated Leader. Files **`Comparaison-accuracy-time.ipynb`** and **`Comparaison-time-limited.ipynb`** compare all algorithms with different criterion.


Dataset is available [here](https://pjreddie.com/projects/mnist-in-csv/) (note that there aren't scaled). 
