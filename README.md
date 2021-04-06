# HR Analytics: Job Change of Data Scientists
## Predict who will move to a new job

Dataset: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

 
### 0) Data Exploration and Visualization <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step0_DataVisualization.ipynb">link</a>  

### 1) Data Preprocessing <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step1_DataPreprocessing.ipynb">link</a>  

### 2) Model Selection <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step2_ModelSelection.ipynb"> link</a>  




### 3) Performance of Final Models

**Annotation**
- Default model: The model using default hyper parameters.
- Final model: The model with tuned hyper parameters.


<a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step3_1_RandomForest_TuningParam.ipynb"> 3.1) Random Forest Model Performance</a>  
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default **       | 0.855                  | 0.933                   |
| **Final **         | 0.860                  | 0.937                   |



<a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step3_2_GMB_TuningParam.ipynb"> 3.2) Gradient Boost Model Performance</a>  
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default**        | 0.855                  | 0.925                   |
| **Final**          | 0.859                  | 0.936                   |



<a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step3_3_XBG_TuningParam.ipynb"> 3.3) Xgboost Model Performance</a>  
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default**        | 0.859                  | 0.935                   |
| **Final**          | 0.862                  | 0.937                   |



