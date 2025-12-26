📌 What is Support Vector Machine (SVM) and What Does It Do?

Support Vector Machine is a margin-based supervised learning algorithm that finds the optimal hyperplane which maximizes separation between classes.

Key concepts:

Support Vectors — critical boundary points that define the decision margin

Maximum Margin — improves robustness and generalization

Kernel Trick — maps data into higher dimensions to separate non-linear patterns

SVM is used for both:

Classification (SVC) — separating classes

Regression (SVR) — fitting a margin-tolerant function

Kernel options explored:

Linear

Polynomial

RBF (Gaussian)

Sigmoid

Each kernel revealed different behaviors in terms of bias-variance trade-offs and boundary complexity.

✔ Advantages of SVM

Works well in high-dimensional feature spaces

Effective on non-linear datasets using kernel trick

Robust against overfitting in well-separated classes

Strong performance on smaller and medium-sized datasets

Well-suited for classification problems with clear margins

✘ Disadvantages of SVM

Computationally expensive on large datasets

Requires careful kernel and hyperparameter tuning

Less interpretable than linear models

Sensitive to feature scaling

Training time increases significantly with dataset size
