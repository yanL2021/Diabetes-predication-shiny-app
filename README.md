# Diabetes Prediction

Context
The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage. UCI Machine Learning: [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

Content
The dataset consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

App functions
1. Exploratory data analysis of the dataset
2. Compare the performance of three models (logistic regression,classification tree, and random forest) in predicting whether or not the patients in the dataset have diabetes or not.
3. Predict the probability of a patient have diabetes by user input values
4. Save the data used in modeling as a csv file.


List of packages needed
`shiny`
`shinydashboard`
`shinyWidgets`
`shinybusy`
`tidyverse`
`caret`
`rsample`
`rpart`
`rpart.plot`
`pROC`
`mathjaxr`

**Please run the code below in R to access the Shiny App:**<br />
install.packages(c("shiny", "shinydashboard", "shinyWidgets", "shinybusy", "tidyverse", "caret", "rsample", "rpart", "rpart.plot", "pROC", "mathjaxr"))<br />
shiny::runGitHub("558project3", "yanL2021",ref = "main")
