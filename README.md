# HR Analytics: Job Change of Data Scientists
## Predict who will move to a new job


Dataset: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

### 0) Data Exploration and Visualization
#### :date: <a href = "https://nbviewer.jupyter.org/github/Wei-Kuang/STA141B/blob/master/HW1/hw1_2019.ipynb">1. The Doomsday Algorithm </a>  

### 1) Data Preprocessing

### 2) Model Selection

### 3) Final models

#### Random Forest Model Performance
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default**        | 0.855                  | 0.933                   |
| **Final Model**    | 0.860                  | 0.937                   |


#### Gradient Boost Model Performance
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default**        | 0.855                  | 0.925                   |
| **Final Model**    | 0.859                  | 0.936                   |


#### Xgboost Model Performance
| Model              | Accuracy (testing set) | AUC score (testing set) |
| :--                | :--                    |:--                      |
| **Default**        | 0.859                  | 0.935                   |
| **Final Model**    | 0.862                  | 0.937                   |


**Footnote**
- Default model: The model using default hyper parameters.
- Final model: The model with tuned hyper parameters.
