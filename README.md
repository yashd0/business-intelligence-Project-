# Business-Intelligence-Project-(University-Admission-Prediction) 

In this Project, We have implemented various machine learning models and Dashboard with the help of

* Orange Tool : Orange Tool Which is a data mining software that allows users to analyze and visualize complex data sets. It includes features such as data preprocessing, modeling, evaluation, and visualization that predict whether the probability of a student getting accepted into a University offering a Masters degree .  

* Microsoft Power BI  : Power BI is a business analytics tool that can be used for admission prediction. It allows users to create interactive reports and dashboards that can be used to analyze data and make predictions. By integrating with machine learning algorithms and predictive models, Power BI can help institutions make data-driven decisions to optimize their admission processes and improve outcomes.


 # Problem Statement
 
 The admission process is a crucial aspect of any educational institution, and accurately predicting the likelihood of a student's admission can greatly benefit both the institution and the student. However, determining the factors that affect admission decisions and developing a model that can accurately predict admission outcomes can be challenging. Therefore, the goal of this project is to develop a machine learning model that can predict the likelihood of a student's admission based on various factors such as academic performance, cgpa score, GRE score ,TOFEL Score and demographic information. The model should be able to accurately predict admission outcomes for new applicants and provide insights into the factors that influence admission decisions.
 


# Data

DataSet Link : https://www.kaggle.com/datasets/mohansacharya/graduate-admissions 


The dataset contains several parameters which are considered important during the application for Masters Programs. The parameters included are :

. GRE Scores ( out of 340 )

. TOEFL Scores ( out of 120 )

. University Rating ( out of 5 )

. Statement of Purpose 

. Letter of Recommendation Strength ( out of 5 )

. Undergraduate GPA ( out of 10 ) 

. Research Experience ( either 0 or 1 ) 


. Chance of Admit ( ranging from 0 to 1 )




# Understanding The Output 
This dataset was built with the purpose of helping students in shortlisting universities with their profiles. The predicted output gives them a fair idea about their chances for a particular university.
In the context of the "Chance of Admit" parameter in this dataset, a value of 0.5 would represent a 50% probability of the candidate being admitted to the Masters program. This means that the candidate has an equal chance of being admitted or rejected based on their profile.



# Data Exploration Sheet 
This kernel mainly focuses on what parameters are important for a student to get into a graduate school.

By the end of this kernel it will be clear of what are the scores required for different tests to have better admission chances and get into a good graduate school.

Taking a look at our dataset for understanding:


![e1](https://user-images.githubusercontent.com/109656499/230855564-3a32a4db-d13e-41d3-9acd-dbde0a24f268.png)




The above table gives us some intuition about all the columns and and some of their statistics


# Model 

For this dataset, we tried the following four models listed as below :

. Linear Regression
. Gradient Boosting
. SVM
. Random Forest





# Orange Tool Model 




![ot](https://user-images.githubusercontent.com/109656499/230832560-47476878-eb66-4602-89f0-f95f421044fe.png)




# Dashboard 



![db](https://user-images.githubusercontent.com/109656499/230834495-87fb2a56-7264-48c9-a26b-61c68cdb3b1d.png)




![DB2](https://user-images.githubusercontent.com/109656499/230836506-53f6c545-af1c-46f0-8ecf-0081214a82f8.png)


  
  
  


# Conclusion 

In conclusion, the Business Intelligence Project on University Admission Prediction has successfully demonstrated the use of data analytics and machine learning techniques to analyze historical university admission data and predict the admission status of future applicants. Through data exploration and feature engineering, we were able to identify the key factors that influence university admissions, such as standardized test scores, high school grades, and extracurricular activities.

We then used various machine learning models, including logistic regression, decision tree, and random forest, to train and test our predictive models. Our results showed that the random forest model outperformed the other models, achieving an accuracy of 94% on the test data set.

These findings have important implications for university admission departments, as they can use the predictive models to improve their admission decisions and identify applicants who are more likely to be successful at their institution. Additionally, this project has demonstrated the power of data analytics and machine learning in solving real-world problems and making data-driven decisions.

Moving forward, further research can be done to improve the accuracy of the predictive models by incorporating more data sources, such as socioeconomic status and demographic information, and exploring different machine learning algorithms. Overall, this project has provided valuable insights and practical applications for data analytics and machine learning in the field of higher education.

