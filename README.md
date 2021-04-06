# HR Analytics: Job Change of Data Scientists
## Predict who will move to a new job

Dataset: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

 
### 0) Data Exploration and Visualization <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step0_DataVisualization.ipynb">link</a>  

### 1) Data Preprocessing <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step1_DataPreprocessing.ipynb">link</a>  

<ul><ul>
<li>Remove unneeded features.</li>
<li>Impute missing values.</li>
<li>Encode ordinal variables.</li>
<li>One hot encode for "Nominal variable.</li>
<li>Impute minor outcom.e</li>
<li>Split the dataset into train and test.</li>
<li>Then, standardize the numeric column based on train set.</li>
</ul></ul>

### 2) Model Selection <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/HR_JobChange/blob/main/HR_Analysis_Step2_ModelSelection.ipynb"> link</a>

I explore the following models to predict the outcome:
<ul><ul>
<li>Logistic Regression</li>
<li>SVM_SGD</li> 
<li>DecisionTree</li> 
<li>Random Forest</li>
<li>Gradient Boost</li>
<li>Xgboost</li>
<li>My voting_clf (ensemble model)</li>
</ul></ul>

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



