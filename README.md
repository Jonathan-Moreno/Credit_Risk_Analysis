# Credit_Risk_Analysis

## Overview
Using supervised machine learning to assess the credit risk of potential loans. 

## Results
Six different machine learning models were used to complete this analysis, each returning different balanced accuracy scores, precisions and recalls.
* Naive Random Oversampling Results:
  * ![Screen Shot 2022-06-23 at 10 17 47 PM](https://user-images.githubusercontent.com/96406929/175467383-1d84cb0d-5be7-497d-a9b7-e64826c4e64b.png)
  * ![Screen Shot 2022-06-23 at 10 17 55 PM](https://user-images.githubusercontent.com/96406929/175467423-f5e8ccc8-4ddb-4ba8-831b-7adeae1b2b4e.png)
  * Balanced accuracry score: ~64%
  * High risk precision: 1%
  * High risk recall: 73%
  * Low risk precison: 100%
  * Low risk recall: 55%
* SMOTE Oversampling Results:
  * ![Screen Shot 2022-06-23 at 10 24 56 PM](https://user-images.githubusercontent.com/96406929/175468142-17310e8e-fc69-4086-9ade-c7d616cc4386.png)
  * ![Screen Shot 2022-06-23 at 10 25 05 PM](https://user-images.githubusercontent.com/96406929/175468165-b6f151b3-7e7b-4629-b1e3-364964815cdc.png)
  * Balanced accuracry score: ~66%
  * High risk precision: 1%
  * High risk recall: 62%
  * Low risk precison: 100%
  * Low risk recall: 69%
* Undersampling Results:
  * ![Screen Shot 2022-06-23 at 10 26 30 PM](https://user-images.githubusercontent.com/96406929/175468315-22726c87-85f4-446f-abd5-aa2aa874b6fa.png)
  * ![Screen Shot 2022-06-23 at 10 26 36 PM](https://user-images.githubusercontent.com/96406929/175468338-295942fd-78c8-4ff3-84f7-d1bcda6a40d9.png)
  * Balanced accuracry score: ~54%
  * High risk precision: 1%
  * High risk recall: 69%
  * Low risk precison: 100%
  * Low risk recall: 40%
* Combination Sampling Results:
  * ![Screen Shot 2022-06-23 at 10 28 35 PM](https://user-images.githubusercontent.com/96406929/175468533-6a782dc9-a69e-4ca5-8be3-604ef27479f5.png)
  * ![Screen Shot 2022-06-23 at 10 28 59 PM](https://user-images.githubusercontent.com/96406929/175468588-97d42d5a-b8ce-48db-96b1-a1b5a0a05f3d.png)
  * Balanced accuracry score: ~64%
  * High risk precision: 1%
  * High risk recall: 72%
  * Low risk precison: 100%
  * Low risk recall: 57%
* Balanced Random Forest Classifier Results:
  * ![Screen Shot 2022-06-23 at 10 30 28 PM](https://user-images.githubusercontent.com/96406929/175468760-c9fc1e47-774c-4fce-b4a9-fb9c9c95d70e.png)
  * ![Screen Shot 2022-06-23 at 10 31 09 PM](https://user-images.githubusercontent.com/96406929/175468802-09a59e6e-1192-4e2d-8d81-8976ce60d22c.png)
  * Balanced accuracry score: ~79%
  * High risk precision: 4%
  * High risk recall: 67%
  * Low risk precison: 100%
  * Low risk recall: 91%
* Easy Ensemble AdaBoost Classifier Results:
  * ![Screen Shot 2022-06-23 at 10 32 07 PM](https://user-images.githubusercontent.com/96406929/175468912-c8e843fe-dca2-4b35-9efb-7f561ad30453.png)
  * ![Screen Shot 2022-06-23 at 10 32 13 PM](https://user-images.githubusercontent.com/96406929/175468926-f6fdc47d-6ad9-4553-92ca-3d6cedc046f7.png)
  * Balanced accuracry score: ~93%
  * High risk precision: 7%
  * High risk recall: 91%
  * Low risk precison: 100%
  * Low risk recall: 94%
  
## Summary
Of all the machine learning models used through out the analysis, I would reccomend using the Easy Ensemble AdaBoost Classifier as it had the highest balanced accuracy score. 

