# levenbergmarquardt
Julia implementation of LM algorithm. Submitted as part of MIT 18.335 (Introduction to Numerical Methods) project.

Many data-fitting problems involve the use of a non-linear fit function. Solving the corresponding non-linear least squares problem requires a good algorithm. The Levenberg-Marquardt algorithm is a common method used to tackle this problem. In this project, we introduce the algorithm, explain its relation with gradient descent and Gauss-Newton, and compare these methods using a set of 10 test problems. We find that the Levenberg-Marquardt algorithm is indeed better than gradient descent and Gauss-Newton for solving non-linear least squares problems. We also review an alternate damping parameter update rule introduced by Nielsen, and verify that it achieves smoother convergence.