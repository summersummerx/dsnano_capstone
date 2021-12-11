# Customer Segmentation Report for Arvato Financial Solutions

## Motivation: 
Arvato Financial Solutions is a mail-order sales company in Germany. This project compared demographics data of Arvato customers against demographics information of the general population. Unsupervised learning was used to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. Supervised learning was used to learn and predict which individuals are most likely to convert to a customer of the compane


## Libraries used:

numpy; 
pandas; 
matplotlib; 
seaborn; 
pickle; 
collections; 
sklearn; 
xgboost

## Files in the repository:

Jupyter Notebook Arvato Project Workbook                                                                                                                                         
Screenshot as proof of participation in the Udacity+Arvato Kaggle Competition                                                                                                     
README.md

## Summary of Results:
1. We have higher percentage of datapoints from cluster no.2 and no.3 in azdias dataset, with cluster no.1 as the lowest. In customers dataset, cluster no.2 and no.0 have high percentage and the lowest percentage is from cluster no.4.                                                                                                                       
2. Based on the percentage of customers within each cluster (combined_seg2 data), cluster no.1 and no.2 have highest customer percentage. In general population, we might want to target sub-population from cluster no.1 and no.2 in future marketing campaigns as there may be a better chance that the campaigns actually reach a potencial customer.           
3. Assuming the azdias dataset is a good representation of the general population, we have the most people from cluster no.2 in general population. And cluster no.2 also has relatively high customer percentage. Thus, cluster no.2 could be the priority in future marketing efforts if given limited budget and time.                                       
4. The prediction model built has a Score of 0.62513 in the Udacity+Arvato Kaggle Competition

## The blog post could be found: 

## Acknowlegement: 
The project is using data provided by Arvato Financial Solutions through Udacity.
