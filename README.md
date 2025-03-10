# Empirical-Evaluation-of-Machine-Learning-Procedures-
- __Overview__  :

Technological advancements have made data collection easier than ever before, raising the ques-
tion of variable selection in econometrics and machine learning more prominently today than in the
past. Particularly when the dataset contains a large number of predictors, it is essential to identify
the most relevant ones to explain the target variable, in order to achieve a parsimonious model
and good predictive performance. This paper revisits various methods, distinguishing between
two categories: Statistical Learning methods (Forward, Backward, Stepwise) and methods used in
Machine Learning (LASSO, LARS, Elastic Net). Several stopping criteria are considered, ranging
from statistical criteria such as the F-test, to information criteria like AIC, and finally predictive
criteria such as K-fold cross-validation and Press. The different methods are first studied under
the assumption of independence among explanatory variables, then in the presence of correlation,
outliers, and finally structural breaks. 

- __Project Description__ :

This article focuses on assessing the effectiveness of various variable selection techniques across four distinct data scenarios. 

For this study, we employed algorithms generating  data under different assumptions : independance, correlation, outliers, structural break and a mix of them, created through Monte Carlo simulations. The true model was defined as comprising an intercept with all variables ranging from X1 to X7. Simultaneously, we calculated performance metrics to evaluate each method's ability to identify the correct model. These metrics encompass perfect-fitting (matching the true model), overfitting (obtaining the true model with additional variables), underfitting (failure to include all true model variables), and wrong models (incorrect selection of additional variables, leading to an incomplete true model representation).

- __Keywords__ :

Statistical learning,
Machine learning,
Forward / backward / Stepwise selection,
Forward Stagewise / LARS / LASSO / ELASTICNET,
AIC / AICc / BIC / K-fold cross-validation / PRESS,
SAS: proc glmselect, proc iml, proc freq

- __Instructions__ 📋:



- __Contributors__ 👩‍🎓:
  
Ibrahim DIABIRA,
Tigran GYURJYAN,
Marwan HAMZAOUI
