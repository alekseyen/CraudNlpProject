# CraudNlpProject
Train paraphrase recognition models for detecting related search queries.
Queries are considered close if they relate to the solution of the same user task.

## Collect dataset
Dataset wes collect using toloka.ai [Examples could be found here](img/examples):

Project settings:

|  ![](img/project/project_1.png)  |  ![](img/project/project_2.png) |
|---|---|

Pool settings:

|  ![](img/pool/pool_1.png) | ![](img/pool/pool_2.png)  |
|---|---|

## Model
Using pytorch-lightning 
with base `bert-base-multilingual-cased` model 
achieved good quality on test dataset, and it cost just 10$.


Loss model with test **Accuracy** 78.67:
![](7867_loss.png)
