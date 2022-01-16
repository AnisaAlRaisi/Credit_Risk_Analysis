# Credit_Risk_Analysis
 
## Overview
### Purpose of this analysis:
The purpose of this analysis is to produce an evaluation of two machine learning models (BalancedRandomForestClassifier and EasyEnsembleClassifier )to see whether they should be used to predict credit risk.

## Results
The following are the results of the six machine learning models:
- RandomOversampler:  Balanced Accuracy score = 0.6497536370265621
<img width="1124" alt="Screen Shot 2022-01-16 at 9 47 07 PM" src="https://user-images.githubusercontent.com/31663190/149671634-b5ff618a-dcca-41b5-9358-b45df63ade95.png">
<img width="736" alt="Screen Shot 2022-01-16 at 9 50 26 PM" src="https://user-images.githubusercontent.com/31663190/149671660-7427c809-193f-4ef5-adc4-937e4f9a7ea6.png">

 
- SMOTEENN: Balanced Accuracy score =0.6376117496807152
<img width="639" alt="Screen Shot 2022-01-16 at 9 51 53 PM" src="https://user-images.githubusercontent.com/31663190/149671720-8272ff7a-4801-49e9-8d49-ecf6d0b2da59.png">
<img width="828" alt="Screen Shot 2022-01-16 at 9 52 00 PM" src="https://user-images.githubusercontent.com/31663190/149671723-8d878fba-c612-4f9d-83db-d41888f7d7b4.png">

- BalancedRandomForestClassifier: Balanced Accuracy score = 0.7663666770091415
<img width="567" alt="Screen Shot 2022-01-16 at 9 53 11 PM" src="https://user-images.githubusercontent.com/31663190/149671772-71e0231d-8e07-4e4e-af9a-e4b63be4ffcd.png"><img width="859" alt="Screen Shot 2022-01-16 at 9 53 16 PM" src="https://user-images.githubusercontent.com/31663190/149671775-14a3a266-54f9-4097-9480-5558b29b8f7a.png">


- EasyEnsembleClassifier: Balanced Accuracy score =0.9316600714093861
- <img width="1144" alt="Screen Shot 2022-01-16 at 9 55 16 PM" src="https://user-images.githubusercontent.com/31663190/149671823-a234cebd-8d45-4755-9e9c-0be284cf6561.png">
<img width="902" alt="Screen Shot 2022-01-16 at 9 55 35 PM" src="https://user-images.githubusercontent.com/31663190/149671825-b7583d61-57df-4ba2-b225-724ef4aee9c8.png">


## Summary

My reccomendation would be to use the EasyEnsembleClassifier model as it has the highest balanced accuracy score as it is closest to 1.
