# Online-convex-optimization

Implementation of different online convex optimizabation algorithms, based on the book of [E. Hazan, 2019](https://ocobook.cs.princeton.edu/OCObook.pdf). We test these algorithms for the problem of learning a linear SVM with MNIST dataset. For simplification, we resctrict the problem of binary classification (0 or other). Our criterion for comparaisons is the test score, expressed as a loss.
In particular, we use some functions for all algorithms : 

- *hingereg*, return regularized hinge loss
- *gradreg*, which return the gradient of the regularized hinge loss
- *hinge_reg_sgd* and *grad_reg_sgd*, same functions for stochastic case


Here is all algorithms we use : 

  - **`nom_du_fichier.ipynb`** : classical stochastic gradient descent (2 versions, with or without projection step)
  - **`nom_du_fichier.ipynb`** : 222
  - **`nom_du_fichier.ipynb`** : 22
