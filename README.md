# HW2_Problem4_Learn_Perceptron_Notebook
## Exploring using Perceptron to classify Penguin data
1. first we should import needed libraries
2. then we should load and prepare the data
3. determine the target and input:\
    target variable = the species & input variables = the numerical
4. Visualizing the data:
    When visualizing data, especially with less than 10 variables, plotting all combinations of two variables helps identify useful features for separation and      detect correlations, with tools like seaborn's "pair plot" providing easy visualization, although large datasets may require subsampling or other methods        to manage data size and processing demands.
5. Key Learnings and Next Steps:
    a. Strong Correlation: Body mass and flipper length exhibit a high correlation.
    b. Variable Selection: For the initial focus, body mass and bill depth are chosen as input variables due to their distinct correlation patterns and the ease     of visualization in 2D.
    c. Species Differentiation: Chinstrap species shows notable differences in bill depth and body mass, making it easier to distinguish from Gentoo and Adele       species.
    d. Simplification for Clarity: The goal is to simplify the classification problem for better understanding. Therefore, focusing on separating either             Chinstrap from Gentoo or Gentoo from Adele is preferred.
    e. Binary Classification: To start with a simpler problem, Chinstrap species will be excluded from the dataset, focusing on binary classification between       Gentoo and Adele.
    f. Accuracy vs. Understandability: While using all variables could increase accuracy, the initial focus is on understandability and clear visualization,         hence the choice of only two variables.
   
