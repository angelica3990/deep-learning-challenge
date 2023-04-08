# deep-learning-challenge

## Overview of Analysis

### Data Preprocessing
- Variables
  - EIN and NAME — Identification columns
  - APPLICATION_TYPE — Alphabet Soup application type
  - AFFILIATION — Affiliated sector of industry
  - CLASSIFICATION — Government organization classification
  - USE_CASE — Use case for funding
  - ORGANIZATION — Organization type
  - STATUS — Active status
  - INCOME_AMT — Income classification
  - SPECIAL_CONSIDERATIONS — Special considerations for application
  - ASK_AMT — Funding amount requested
  - IS_SUCCESSFUL — Was the money used effectively

- What variable(s) should be removed from the input data because they are neither targets nor features?
  - EIN and NAME were orginially removed, in my optimized model, only EIN was removed.

### Compiling, Training, and Evaluating the Model
  - Created a Sequential model is using keras and Tensorflow. 
  - Model was compiled and fitted to training dataset.
  - Accurary before optimization is:

![image](https://user-images.githubusercontent.com/62813833/230728433-9532bd8e-b54b-413b-838e-277da8329eff.png)

(72%)


### Optimization
  - Model was able to achieve over 75% accuracy
      - Looked at NAME value counts for binning
   
![image](https://user-images.githubusercontent.com/62813833/230728671-eeea054b-ad30-41c6-b22d-df31c44161e9.png)

(78%)
