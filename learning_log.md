Learning Log:

• Make at least four separate entries reasonably spaced over a period of atleast six weeks
• The entries can either be separate files or different sections within the same file.
• They should be written using Markdown and stored in a private repository on GitHub.
• You need to commit and push each entry as you make it so that the dates of the entries are correctly recorded in git.
• You can include images and external links. For each entry identify:
• What you have done (to learn your skill and contribute to your project)
• What you have learned
• Any changes to your goals (or what your initial goals are for the firstentry)
• Next step(s) to achieve your goalsThe learning log should have a maximum total word count of 1500 words, asmeasured by the Microsoft VS Code Word Count plugin and have a reasonablebalance between the entries

Entry 1:

• Any changes to your goals (or what your initial goals are for the first entry).

- The goal is to cover the bulk of the coursera Andrew Ng Machine Learning course content and build an unsupervised machine learning model (potentially image classification).

• What you have done (to learn your skill and contribute to your project)?

- I have enrolled in the Andrew Ng Machine Learning course on coursera and completed the first week of the

• What you have learned?

- I have completed week 1 of course, titled "Introduction to Machine Learning"
- I have learned about the subfields of supervised ML (regression, classification etc.) and unsupervised ML, as well as cost functions and training a model with gradient descent.

• Next step(s) to achieve your goals:

- Complete the first 3 weeks of the Andrew Ng course whilst taking notes and thinking of specific project ideas.

Entry 2:

• What you have done (to learn your skill and contribute to your project)

- I have now covered weeks 1 - 3 of the coursera Andrew Ng Machine Learning course content. I have watched all of the videos and taken notes.

• What you have learned?

In short, the content covered included:

- Week 2: Multiple linear regression, vectorisation (making code implementation of ML algorithms much shorter and code run faster), gradient descent with multiple linear regression, (including feature scaling, learning rates, feature engineering, polynomial regression etc.)

- Week 3: Logistic regression (which predicts the probability that something is true or false, therefore normally used for classification), decision boundaries, the logistic loss function for gradient descent, the logistic regression gradient descent algorithm, bias and variance, overfitting and the ways of reducing it.

• Any changes to your goals?

- We're still set on an image classification project. I'll complete the first 6 weeks of the Andrew Ng course so that I have a basic understanding of the background mathematics of a CNN image classification algorithm, although I'll obviously use a library to implement the model anyway.

• Next steps:

- Source data for said project
- Specify a model (with parameters, cost function, gradient descent algorithm etc) and train said model on the data.
- Undergo an iterative process of evaluating the bias/variance of the model and improving it based off these two factors.

Entry 3:

- Week 4: The Neural Network Model, including:

  - Hidden layers and how every layer inputs a vector of numbers and applies a bunch of logistic regressions to it, then computes another vector of numbers that are passed from layer to layer, culminating in a final layer where you get the prediction of the neural network.
  - Inference (forward propogation), both conceptually and its code implementation in TensorFlow.
  - Building a neural network architecture.

- Week 5: Neural Network Training:

  - Training a Neural Network in TensorFlow (code implementation)
  - The steps of model training:
    - 1. Defining the model
    - 2. Specifying the loss and cost functions
    - 3. Training on data to minimize J(w,b).
  - Various different activation functions other than Sigmoid that can be used depending on the given data (e.g. use ReLU for housing price prediction because it will never be negative)
  - The softmax architecture for non-binary input classification (more than two inputs).

- Week 6: Advice for applying an ML model:
  - How to evaluate a model (for classification and linear regression):
    - The 70/30 training set/test set split to analyse a model's performance
    - Alternatively measure the fraction of the test set and training set that the algorithm has misclassified.
  - What bias and variance are. J(cv) and J(train) give you a rough idea of whether your algorithm has high variance/bias.
  - Diagnosing bias and variance.
  - Cross-validation is used to make a good choice for the regularization value lambda
  - Cross validation tries out a lot of different values of lambda, and picks out a value with low cross-validation error.
  - Learning curves
  - The iterative loop of ML development and full cycle of a ML project.

• Any changes to your goals?

- Instead of an unsupervised project, I will look to build a supervised ML model that allows me to put the whole "cycle" of a machine learning project into practice, from defining the project through to collecting data, training, error analysis and iterative improvement.

• Next step(s) to achieve your goals

- Select a project (leaning towards a CNN/binary classification model of dog/cat images).
- Source data for said project
- Specify a model (with parameters, cost function, gradient descent algorithm etc) and train said model on the data.
- Undergo an iterative process of evaluating the bias/variance of the model and improving it based off these two factors.
