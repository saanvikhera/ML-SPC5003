
### Tutorial 1 – Python Fundamentals and Data Handling

**Main topics:**
- Python functions and reusable code.
- Classes and object-oriented programming.
- Mean Squared Error (MSE) and Mean Absolute Error (MAE).
- Linear models and standardisation.
- Vectorisation using NumPy.
- Creating, saving and loading datasets using pandas.
- Data visualisation using Matplotlib.
- Exploring relationships between variables using correlation.

**Key learning:** Understanding how to organise code into reusable functions and classes, and how vectorised operations can make numerical computations more efficient than using explicit loops.

### Tutorial 2 – Linear Regression and Gradient Descent

**Main topics:**
- Generating synthetic datasets.
- Linear regression: ŷ = wx + b.
- Mean Squared Error as a cost function.
- Calculating gradients with respect to weights and biases.
- Numerical gradient checking using finite differences.
- Implementing gradient descent.
- Understanding the effect of different learning rates.
- Comparing an implemented regression model with NumPy's `polyfit`.

**Key learning:** Understanding how a model learns by iteratively adjusting its parameters to minimise a cost function.

### Tutorial 3 – Logistic Regression and Classification

**Main topics:**
- Binary classification.
- The sigmoid activation function.
- Converting predicted probabilities into class labels using a threshold.
- Binary cross-entropy loss.
- Calculating gradients for logistic regression.
- Training using gradient descent.
- Evaluating classification models.
- Confusion matrices, accuracy, precision, recall and F1-score.
- Investigating how changing the classification threshold affects evaluation metrics.

**Key learning:** Understanding the difference between regression and classification, and why different loss functions and evaluation metrics are needed for different machine learning tasks.

### Tutorial 5 – Forward and Backward Propagation

**Main topics:**
- Neural network architecture.
- Forward propagation through output and hidden neurons.
- ReLU and sigmoid activation functions.
- Binary cross-entropy loss.
- Backpropagation using the chain rule.
- Calculating gradients for weights and biases.
- Gradient descent in neural networks.
- Investigating learning rates and inactive hidden neurons.
- Extending a network from one hidden neuron to two.
- Comparing analytical gradients with numerical gradients.

**Key learning:** Understanding how neural networks calculate predictions and how errors are propagated backwards through the network to determine how each parameter should be updated.

### Tutorial 6 – Stochastic and Batch Gradient Descent

**Main topics:**
- Training neural networks using multiple training examples.
- Stochastic gradient descent (SGD).
- Batch gradient descent.
- Comparing individual-example loss with average dataset cost.
- Implementing forward and backward propagation.
- Matrix multiplication and vectorisation.
- Understanding matrix dimensions and weight shapes.
- NumPy broadcasting and transposes.
- Comparing training behaviour and loss curves.

**Key learning:** Understanding how different gradient descent approaches update model parameters and how matrix operations allow neural networks to process multiple examples efficiently.

## 3. Overall Development

Across these tutorials, the work develops through several stages:

1. **Programming foundations:** Writing functions, classes and efficient NumPy operations.
2. **Data handling:** Generating, loading, processing and visualising datasets.
3. **Regression:** Implementing linear regression and optimising model parameters.
4. **Classification:** Implementing logistic regression and evaluating predictions.
5. **Neural networks:** Building networks with hidden layers and different activation functions.
6. **Optimisation:** Implementing backpropagation, SGD and batch gradient descent.

A recurring concept throughout the repository is gradient descent. It is first introduced through linear regression, then applied to logistic regression and eventually extended to neural networks.

## 4. Potential Viva Questions

### Python and Data Handling
- What is the difference between a function and a class?
- What is vectorisation, and why is it useful?
- What is standardisation, and why might we need it?
- How did you load and visualise a dataset?

### Regression and Optimisation
- What is the difference between linear and logistic regression?
- What does the cost function measure?
- What is a gradient?
- How does gradient descent update weights and biases?
- What happens if the learning rate is too high or too low?
- Why do we use numerical gradient checking?

### Classification
- What does the sigmoid function do?
- Why is binary cross-entropy used for logistic regression?
- What is the difference between precision and recall?
- What does a confusion matrix show?
- How does changing the classification threshold affect predictions?

### Neural Networks
- What is forward propagation?
- What is backpropagation?
- What is the chain rule, and why is it important?
- What is the difference between ReLU and sigmoid?
- What are weights and biases?
- Why might a hidden neuron produce zero gradients?
- How does a neural network learn from its errors?

### Gradient Descent and Implementation
- What is the difference between stochastic and batch gradient descent?
- What is an epoch?
- Why does the SGD loss curve tend to be more jagged?
- Why do we divide gradients by the number of training examples in batch gradient descent?
- What does matrix multiplication achieve in neural network implementations?
- Why are matrix dimensions important?

## 5. Reflection

The tutorials demonstrate a progression from implementing individual mathematical operations to developing complete machine learning training procedures.

One of the most important developments is understanding that machine learning models do not simply produce predictions: they use a defined loss function, calculate gradients and iteratively adjust their parameters to improve performance.

The neural network tutorials build on the earlier regression work by introducing multiple layers, activation functions and the chain rule. The final tutorial extends these ideas to multiple training examples and matrix-based implementations, demonstrating how the same underlying principles can be applied more efficiently.

