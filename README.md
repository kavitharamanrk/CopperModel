# Copper Model 
Predicting selling price and the status using trained ML model

# Workflow
* Checking null values, zeroes and negative values in the given copper data set
* Replacing null,zero,-ve values with median and mode values
* Checked skewness using different plots
* For removing skewness data log transformation has done
* IQR method also used for data transformation
  
# Selling Price prediction
* quantity tons, width, thickness column has taken for selling price prediction under regression model
* 3 different algorithm has used to predict selling price
* best method has taken for prediction
* pickle file created for the selected model

# Status prediction
* country, thickness etc 8 features has taken for status prediction under categorical model
* 5 different algorithm has used to prediction status
* best method gradient decisiontreeclassifier has used for prediction
* pickle file created for the selected model
  
# Streamlit page
* streamlit page has created for getting inputs from the user for selling price and status prediction
  
