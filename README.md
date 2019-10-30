# IEEE-Fraud-Detection

## Problem Statement
In day today's electronic world ,almost everyone make a transaction either in shopping mall or in booking movie tickets or flight tickets etc.So fraud transaction can happen in any of these places which will penalize the customer heavily as well as the businesses. Hence improving  the efficacy of fraudulent transaction alerts for millions of people around the world and helping hundreds of thousands of businesses reduce their fraud loss and increase their revenue. 
## Source/Useful Links
IEEE-CIS works across a variety of AI and machine learning areas, including deep neural networks, fuzzy systems, evolutionary computation, and swarm intelligence. Today they’re partnering with the world’s leading payment service company, Vesta Corporation, seeking the best solutions for fraud prevention industry.
The data has been collected from Vista's real-world e-commerce transactions and it contains a wide range of features from device type to product features.
Source : https://www.kaggle.com/c/ieee-fraud-detection
## Data Overview
- The data contains 2 csv file one for transaction and another for identity.
- Train file of identity contains 144233 rows and 41 features.
- Train file of transaction contains 590540 rows and 394 features.
## Contents
- I have split the whole notebook into three parts first part is in depth analysis of each feature and generating new features.
- In the second part i have removed some of the unnecessary features through corelation and feature importance method.
- In the third part i have applied different model from logisitc regression to LGBM.And hypreparameter tunned all the models to get best auc value.
## Increase in AUC from 94.08 to 95.89
- I incorporated the magic feature done by the first place solution link: https://www.kaggle.com/cdeotte/xgb-fraud-with-magic-0-9600
getting auc from 94.08 to 95.89 in public leader board.
- I have highlighted in the third part where i have incorporated that changes.
## Credits
- https://www.kaggle.com/c/ieee-fraud-detection/discussion/100400
- https://www.kaggle.com/c/ieee-fraud-detection/discussion/99987
- https://www.kaggle.com/c/ieee-fraud-detection/discussion/107697#latest-620107
- https://www.kaggle.com/jesucristo/fraud-complete-eda
- https://www.kaggle.com/nroman/eda-for-cis-fraud-detection
- https://www.kaggle.com/yasagure/places-after-the-decimal-point-tell-us-a-lot
- https://www.kaggle.com/jolly2136/eda-fe-xgb
- https://www.kaggle.com/yasagure/fraud-makers-are-earnest-people-about-browser
## Blog
- I have written a detailed blog on this case study.
- Link : https://medium.com/@gtavicecity581/ieee-fraud-detection-469398ce1ac4
