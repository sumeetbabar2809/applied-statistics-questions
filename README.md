# applied-statistics-questions
Interview Questions and Answers
This repository contains solutions to 50 common interview questions, along with detailed explanations for five of these questions. The goal is to help you prepare effectively for technical interviews by providing clear, concise answers and deeper insights into key topics.

Table of Contents
Vector in Mathematics
Vector vs. Scalar
Operations on Vectors
Multiplying Vectors by a Scalar
Magnitude of a Vector
Direction of a Vector
Square Matrix vs. Rectangular Matrix
Basis in Linear Algebra
Linear Transformation
Eigenvector
Gradient in Machine Learning
Backpropagation in Machine Learning
Concept of a Derivative in Calculus
Partial Derivatives in Machine Learning
Probability Theory
Components of Probability Theory
Conditional Probability
Bayes Theorem
Random Variable
Law of Large Numbers
Central Limit Theorem
Discrete vs. Continuous Probability Distributions
Measures of Central Tendency
Percentiles and Quartiles
Detecting and Treating Outliers
Central Limit Theorem for Discrete Distributions
Goodness of Fit Tests
Joint Probability Distribution
Calculating Joint Probability Distribution
Joint vs. Marginal Probability Distribution
Covariance of Joint Probability Distribution
Independence of Random Variables
Correlation Coefficient and Covariance
Sampling in Statistics
Sampling Methods
Central Limit Theorem in Statistical Inference
Parameter Estimation vs. Hypothesis Testing
P-Value in Hypothesis Testing
Confidence Interval Estimation
Type I and Type II Errors
Correlation vs. Causation
Confidence Interval Definition
Confidence Level Representation
Hypothesis Testing in Statistics
Null Hypothesis in Hypothesis Testing
One-Tailed vs. Two-Tailed Test
Experiment Design
Key Elements of Experiment Design
Sample Size Determination
Mitigating Bias in Experiment Design
Detailed Explanations
Here are detailed explanations for five key questions:

11. What is the gradient in machine learning?
In machine learning, the gradient is like a slope that shows us how to change our model to make better predictions. Think of it as a guide telling us which direction to move in to reduce errors.

Loss Function: This is like a score that shows how wrong our model's predictions are. Our goal is to make this score as low as possible.
Gradient Descent: This is a step-by-step process where we use the gradient to adjust our model's settings (like weights) to reduce the loss function.
Imagine you are at the top of a hill (high loss) and want to reach the bottom (low loss). The gradient tells you which way to go to get down the hill fastest.

12. What is backpropagation in machine learning?
Backpropagation is a method used to train neural networks (models that mimic the human brain) by adjusting the model’s settings (weights) to make better predictions.

Forward Pass: First, we feed input data through the network to get an output (prediction).
Calculate Error: We compare the prediction to the actual answer and calculate the error (how wrong the prediction is).
Backward Pass: We then move backward through the network, using the error to adjust the weights so that the model will make better predictions next time.
Think of it as teaching a child to throw a ball: you let them throw (forward pass), see where it lands (calculate error), and then give feedback on how to improve the throw (backward pass).

21. What is the central limit theorem, and how is it used?
The central limit theorem is a key idea in statistics that says if you take a lot of random samples from any population, the average of those samples will form a normal (bell-shaped) distribution, even if the original data is not normal.

Why It’s Useful: This theorem allows us to make predictions about a whole population based on a sample. For example, if we measure the average height of 100 people randomly selected from a city, we can use the central limit theorem to estimate the average height of everyone in the city.
Imagine pulling random handfuls of candies from a big jar. If you do this enough times, the average number of each type of candy in your handfuls will be close to the average in the whole jar.

34. What is sampling in statistics, and why is it important?
Sampling is the process of selecting a small group of individuals from a larger population to study. It’s important because studying the entire population is often impractical.

Types of Sampling:
Random Sampling: Everyone has an equal chance of being chosen. This is like drawing names from a hat.
Stratified Sampling: The population is divided into groups, and samples are taken from each group. This ensures all groups are represented.
Cluster Sampling: The population is divided into clusters, and some clusters are chosen randomly. All members of chosen clusters
