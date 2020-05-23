# 1.exploratory-data-analysis-MLR

Predicting the Wine Quality Using Multiple Linear Regression (MLR)

- Exploring the dataset and identifying the problem
- Multiple linear regression
- Implementing the solution
- Evaluating and improving the model
- Analyzing the result

### Exploring the dataset and identifying the problem

#### Wine Data

[Vinho verde][1], is a unique product from the Minho region of Portugal. This wine accounts for 15% of the total Portuguese production. The data was collected from May 2004 to Feb 2007 using only protected designation of origin samples tested by the official certification entity (CVRVV), recorded by a computerized system (iLab), which automatically manages wine sample testing from producer requests to lab and sensory analysis.<br>
Due to privacy and logistic issues, only physicochemical and sensory variables are available.

#### Wine Quality Dataset

- Input variables(based on physicochemical tests):

        - Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sufur dioxide, density, pH, sulphates, alcohol

- Output variable(based on sensory data):

        - Quality, with a score between 0 and 10

![Dataset][2]

# Evaluating and improving the model

#### Backward Elimination

- Step 1 - select the significance level (for example, SL = 0.05)
- Step 2 - fit the model with all independent variables
- Step 3 - choose independent variable with highest P-value, if P-value > SL , go to step 4, otherwise the model is done.
- Step 4 - remove the independent variable.
- Step 5 - fit model without this variable and go to step 3.

# Analyzing the result

![predicted wine result][3]

In general, we can conclude that the results obtained in the context of the experiment considered are not very applicable in practice. The model under study must be refined or revised.

[1]: https://en.wikipedia.org/wiki/Vinho_Verde
[2]: img/dataset.PNG
[3]: img/predicted_result.png
