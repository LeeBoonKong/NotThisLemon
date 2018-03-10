# NotThisLemon!
When life gives you lemons but you'll never want a lemon car! Let's prevent that with the help of data science!

-Compare multiple machine learning algorithms.  
Measured using Mean Squared Error and R2 Score  
Results so far:  
Random Forest Classifier:  
MSE: 0.12445763873  
R2: -0.153979172038  
  
Gradient Boosting Classifier:    
MSE: 0.122402374971  
R2: -0.134922635252  
  
Ada Boost Classifier:  
MSE: 0.123087462891  
R2: -0.141274814181  

Extreme Gradient Bossting Classifier:  
MSE: 0.122744918931  
R2: -0.138098724717  
  
-Data cleaning and null removal.  
1. Replaced null numerical values with the mean of the column.  
2. Replaced null string values with the most common value of the column.  
3. Data scaled using Robust Scaler in sklearn.  
  
-Determine whether a feature is important in recognizing lemons(Soon)  
-Use Deep Learning approach for prediction(Soon)  

##TODO  
Include more features such as Model and TRIM
