# HR Analytics: Job Change of Data Scientists
## Predict who will move to a new job


Dataset: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

### Data Exploration and Visualization

### DataPreprocessing

### ModelSelection

### Final models

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
