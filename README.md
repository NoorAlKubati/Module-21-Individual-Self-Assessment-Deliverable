# Module-21-Individual-Self-Assessment-Deliverable

My role was analysing the Machine learning. I used the the logistic regression in the final project in perticular I used the nueral network. Overall, the analysis started with a quick look at the data after they were loaded into a Pandas data frame. Specifically, the unique values in each variable were extracted to get an idea of which variable(s) needed to be recoded or dummy coded so that they are ready for the analysis. There were mainly three variables that needed to be recoded, namely parkCode, showers, and state. Upon examining each variable closely, it was found that the categories in each variable were not equally distributed. Therefore, the underrepresented categories were bucketed into one category called 'other'. Following that, all categorical variables were recoded using OneHotEncoder. The resulting variables were saved into a separate data frame that was later merged witht the original one. The original variables were removed after they have been recoded, and the resulting target variables (the recoded park code variables) were saved into a separate dataframe called 'Y'. We were left with 45 variables in the original data frame that will be used as features for the analysis. Having done that, the data were split into test and train data and then scaled.
After all these steps were completed successfully, a new TensoFlow Keras instance was initiated to create our neural network model. Then our model was compiled and the data were fit to the model. As the results reveal, we were able to achieve over 90% accuracy with very limited loss in the model. 
