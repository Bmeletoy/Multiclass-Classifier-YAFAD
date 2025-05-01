🧠 Multiclass Classification & Linear Models from Scratch
View Project on GitHub
Languages: Python | Libraries: scikit-learn, NumPy

This project demonstrates my implementation of foundational machine learning algorithms from scratch, focusing on multiclass classification strategies and linear models with gradient-based optimization. The goal was to build these core components manually to deepen my understanding of algorithmic behavior and model evaluation.

🧩 Project Breakdown:
🔹 Multiclass Classification
Implemented One-vs-All (OAA) and Balanced Tree-based multiclass reduction strategies for text-based wine classification.

Used Decision Trees (e.g., stumps and depth-3 trees) to predict wine types based on word features from wine descriptions.

Evaluated accuracy on both a 20-class dataset and a simplified 5-class subset.

Analyzed word importance for specific wine types (e.g., most indicative terms for Sauvignon Blanc and Pinot Noir).

Compared prediction strategies using class confidence vs. binary outputs.

🔹 Gradient Descent from Scratch
Built a custom gradient descent algorithm with adaptive step sizes to minimize convex and non-convex functions.

Verified convergence using trajectory plots and explored impact of initialization and learning rate on optimization.

Extended the gradient descent to support multi-dimensional inputs.

🔹 Linear Classifiers
Developed a modular linear classifier using L2-regularized loss minimization.

Implemented multiple loss functions:

✅ Squared Loss

🔜 Logistic Loss

🔜 Hinge Loss

Integrated my custom gradient descent to optimize model weights across loss types.

Evaluated performance on 2D linearly separable data and binary wine classification tasks.

Interpreted model weights to identify most indicative words for wine classification.

📄 Files Included:
multiclass.py: Multiclass classification strategies (OAA, Tree-based)

gd.py: Custom gradient descent optimizer

linear.py: Linear classifier framework with pluggable loss functions

writeup.pdf: Explanations, analysis, and empirical results

