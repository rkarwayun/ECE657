# RBF Neural Network.


Creating RBF NN to approximate mapping defined by:

f(x1, x2) = +1 if (x1^2 + x2^2 <= 1) and -1 if (x1^2 + x2^2 > 1).

441 points were randomly sampled defined as:

x = (x1, x2) where x1 = -2 + 0.2 * i (where i = 0, 1, .... 20) and x2 = -2 + 0.2 * j (where j = 0, 1, .... 20)

Split into train/test sets (80%/20%).

#### Scenarios:
1) All points in training set are used centers of the RB functions.

2) 150 points are selected as centers of the RB functions such as:

    a) 150 points are randomly chosen.
    
    b) 150 centers found using KMeans.
