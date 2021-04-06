# HR Analytics: Job Change of Data Scientists
## Predict who will move to a new job

Dataset: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

 
### <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step0_DataVisualization.ipynb"> 0) Data Exploration and Visualization</a>  

### <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step1_DataPreprocessing.ipynb"> 1) Data Preprocessing</a>  

### <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step2_ModelSelection.ipynb"> 2) Model Selection</a>  


### 3) Performance of Final Models

\t **Annotation**
\t - Default model: The model using default hyper parameters.
\t - Final model: The model with tuned hyper parameters.


<a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step3_1_RandomForest_TuningParam.ipynb"> 3.1) Random Forest Model Performance</a>  
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default **       | 0.855                  | 0.933                   |
| **Final **         | 0.860                  | 0.937                   |


#### Gradient Boost Model Performance
<a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step3_2_GMB_TuningParam.ipynb"> Gradient Boost Model Performance</a>  
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default**        | 0.855                  | 0.925                   |
| **Final Model**    | 0.859                  | 0.936                   |


#### Xgboost Model Performance
<a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step3_3_XBG_TuningParam.ipynb"> Xgboost Model Performance</a>  
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default**        | 0.859                  | 0.935                   |
| **Final Model**    | 0.862                  | 0.937                   |



