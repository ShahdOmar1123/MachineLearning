🧠 Support Vector Machine (SVM)

Support Vector Machine (SVM) is a supervised machine learning algorithm mainly used for classification and sometimes for regression tasks.

Goal: Find the best boundary (called a hyperplane) that separates data points of different classes.

Support Vectors: These are the critical data points closest to the decision boundary. They “support” or define the position of the hyperplane.

Maximum Margin: SVM tries to maximize the margin, i.e., the distance between the hyperplane and the nearest data points of each class. A larger margin usually means better generalization on unseen data.

Linear vs. Nonlinear:

If the data is linearly separable, SVM draws a straight line (2D) or plane (3D).

If the data is not linearly separable, SVM uses a kernel trick (e.g., polynomial, RBF) to transform data into a higher dimension where it can be separated.

✅ Advantages:

Works well with both linear and nonlinear data.

Effective in high-dimensional spaces.

Robust against overfitting, especially when dimensions are greater than the number of samples.

⚠️ Limitations:

Training can be slow on very large datasets.

Choosing the right kernel and parameters (C, gamma) is crucial for good performance.

🔎 Example Use Cases:

Image classification

Text categorization (spam detection, sentiment analysis)

Bioinformatics (gene classification, cancer detection)
