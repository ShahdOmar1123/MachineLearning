📌 Gradient Descent
Gradient Descent is an optimization algorithm used to minimize a loss function in machine learning models.
The main idea is to iteratively update the model parameters (weights) in the opposite direction of the gradient until the function reaches its minimum.
⚙️ How Gradient Descent Works

Initialize parameters (e.g., weights) with random values.

Compute the loss function for the model.

Calculate the gradient of the loss function with respect to the parameters.

Update the parameters using the formula:
θnew​=θold​−α⋅∇J(θ)
θ: model parameters (weights).
α: learning rate (step size).
∇J(θ): gradient of the loss function.
Repeat until convergence (when the loss no longer decreases significantly).
🔑 Types of Gradient Descent

Batch Gradient Descent

1-Uses the entire dataset to update parameters.

2-Accurate but slow for large datasets.

Stochastic Gradient Descent (SGD)

1-Updates parameters using one sample at a time.

2-Faster, but noisier updates.

Mini-Batch Gradient Descent

1-Uses a small batch of samples for each update.

2-Balances speed and stability.

3-Most commonly used in practice.
