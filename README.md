# NYC-Rental-Prediction
## Data Source
The dataset 'rentalnew' has been preprocessed in Analysis & Visualization part, longitude and latitude are generated and added into dataset so as to predict 'rent' based on independent variables.

## Dataset
rental_id: the id of apartment unit.   
building_id: the id of apartment building.  
rent: the rent of apartment.  
bedrooms: bedroom amount.  
bathrooms: bathrooms amount.   
size_sqft: apartment size.    
min_to_subway: apartment to nearest subway stop walking time.      
floor: the floor of apartment.     
building_age_years: apartment building history.    
no_fees: free amenity fee or not.    
has_roofdeck: has roof-deck or not.    
has_wahser_dryer: has washer + dryer or not.    
has_doorman: has doorman or not.     
has_elevator: has elevator or not.     
has_dishwasher: has dishwasher or not.     
has_patio: has patio or not.    
has_gym: has gym or not.    
neighborhood: third-level region.     
submarket: second-level region.    
borough: first-level region.     
longitude: submarket longitude.    
latitude: submarket latitude.     
For dummy variables (10-17): 1 == YES, 0 == NO.

## Inspiration
Data Preprocessing   
1.1 Missing Value     
1.2 Categorical Encoding      
1.3 Feature Processing   
  1.3.1 Transformation  
  1.3.2 Distribution  
  1.3.3 Outlier  
  1.3.4 Correlation  
  1.3.5 Normalization  
  1.3.6 Importance    
 
Prediction   
2.1 Cross Validation    
2.2 Polynomial Transformation   
2.3 Hyperparameter Tuning   
2.4 Modeling   
  2.4.1 Linear Regression    
  2.4.2 Lasso Regression    
  2.4.3 ElasticNet Regression  
         
Prediction after Feature Selection    
Conclusion    
Future Improvement
