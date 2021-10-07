# Credit_Risk_Analysis

## Purpose of the analysis

The purpose of this analysis is use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling that predict the credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 

## Results

### Naive Random Oversampling
- Accuracy Score: 65.34%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 63%
- Recall Low Risk: 67%

 <img width="885" alt="Screen Shot 2021-10-07 at 2 38 08 PM" src="https://user-images.githubusercontent.com/81284888/136466145-83794684-de7e-4d3a-bb39-36516618c4ff.png">

### SMOTE Oversampling 
- Accuracy Score: 65.12%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 64%
- Recall Low Risk: 66%

<img width="826" alt="Screen Shot 2021-10-07 at 2 38 21 PM" src="https://user-images.githubusercontent.com/81284888/136466205-b17adbd8-70cf-4c67-acd2-a02041f5ab9a.png">

### Undersampling
- Accuracy Score: 51.03%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59%
- Recall Low Risk: 43%

<img width="820" alt="Screen Shot 2021-10-07 at 2 38 33 PM" src="https://user-images.githubusercontent.com/81284888/136466248-c760e454-fb22-424d-9fae-0b28ce94ce24.png">

### Combination (Over and Under) Sampling
- Accuracy Score: 51.03%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 70%
- Recall Low Risk: 57%

<img width="808" alt="Screen Shot 2021-10-07 at 2 38 44 PM" src="https://user-images.githubusercontent.com/81284888/136466300-25c85785-5071-4dc7-833a-64196367c156.png">
