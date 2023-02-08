# **Respuestas Examen DP-100**

## **Topic 1 - Question Set 1**

1. Answer:
   1. 4 GB of system RAM
   2. BIOS-enabled virtualization
   3. Windows 10 64-bit
2. GPU
3. Ubuntu 16.04 DSVM
4. **NO**
5. **NO**
6. **YES**
7. Answer:
   1. AzCopy
   2. SSIS
   3. Azure Storage Explorer
8. ARFF
9. You should consider including TensorFlow
10. **NO**
11. **YES**
12. You should make use of the Split Data module
13. You should add the Import Data object to the pipeline
14. **YES**
15. **YES**
16. **YES or NO**
17. Convert to indicator values
18. No adjustment required
19. Box plot
20. You should consider configuring the use of Azure Notebooks
21. **Probabilistic PCA** or **Median** or **Custom substitution value**
22. You should consider using the Binary classification confusion matrix visualization
23. **NO**
24. Answer:
    * It must be whole numbers
    * It must be a positive value
25. **NO**
26. **NO**
27. **NO**
28. Answer:
    * You have a matched pairs of scores
    * The sampling distribution of d is normal
29. Should A, if not exist a option: **Blocked Algorithm**
30. You should make use of the featurization parameter with the 'auto' value pair
31. Boosted Decision Tree Regression
32. **NO**
33. **NO**
34. **YES**
35. Answer:
    * Precision
    * Accuracy
36. Answer:
    * Random number seed
    * The initial learning weights diameter
    * Number of learning iterations
37. You should consider making use of the Random grid sweep mode
38. You have to add L1/L2 regularization, and make use of training data augmentation
39. **NO**
40. **NO**
41. **YES**
42. Train, Score, Evaluate

## **Topic 2 - Question Set 2**

1. Answer:
   1. BIOS-enabled virtualization
   2. Windows 10 64-bit Professional
2. Build the environment in Azure Databricks and use Azure Data Factory for orchestration
3. Answer:
   1. Create an Azure Databricks cluster
   2. Install the Azure Machine Learning SDK por Python on the cluster
   3. Create and exceute a Jupyter notebook by using automated machine learning (AutoML) on the cluster
   4. When the cluster is ready and has processed the notebook export your Jupyter notebook to a local environment
4. Azure Machine Learning Service (specifically DSVM)
5. Create a Data Science Virtual Machine (DSVM) Windows edition
6. Azure HDInsight with Spark MLib
7. Answer:
   1. AzCopy
   2. Azure Storage Explorer
   3. Python script
8. Convert to ARFF
9. TensorFlow
10. Graphic Processing Unit (GPU)
11. Data Science Virtual Machine for Linux (Ubuntu)
12. Answer:
    1. Vocabulary mode: Create
    2. N-Grams size: 3
13. Azure Container Service
14. Synthetic Minority Oversampling Technique (SMOTE)
15. Answer:
    1. Build DNN models: Vowpal Wabbit
    2. Enable interactive data exploration and visualization: PowerBI Desktop
16. Partition and Sample
17. Answer:
    1. Import Data
    2. Clean Missing Data
    3. Partition and Sample
18. Answer:
    1. Partition or sample mode: Sampling
    2. Random seed for sampling: 0
19. Remove entire row
20. Answer:
    1. register_azure_blob_container
    2. create_if_not_exists = False
21. Out of scope, ALL RESPONSES (A,B,C,D,E)
22. Answer:
    1. Datastore
    2. ws
    3. demo_datastore
23. D. Create a tabular dataset that references the datastore and explicitly specifies each 'sales/mm-yyyy/sales.csv'. Register the dataset with the name sales_dataset ach month as a new version and with a tag named month indicating the month and year it was registered. Use this dataset for all experiments, identifying the version to be used based on the month tag as necessary
24. Answer:
    1. mlc_cluster
    2. aks_cluster
25. Answer:
    1. A new machine learning compute resource is create with a virtual machine size of STANDARD_DS12_v2 and a maximum of four nodes: NO
    2. Any experiments configured to use `the_cluster` will run on ComputeOne: NO
    3. The text **Step1** will be printed to the screen: YES
26. Answer:
    1. STANDARD_NC12       12      2       112 GB      680 GB
    2. STANDARD_NC24       24      4       224 GB      1,440 GB
27. Answer:
    1. Replace missing values by removing rows and columns: **Clean Missing Data**
    2. Increase the number of low-incidence examples in the dataset: **SMOTE**
    3. Convert a categorical feature into a binary indicator: **Convert to Indicator Values**
    4. Remove potential duplicates from a dataset: **Remove Duplicate Rows**
28. **NO**
29. Answer:
    1. If a compute cluster named aml-cluster already exists in the workspace, it will be deleted and replaced: **NO**
    2. The `wait_for_completion()` method will not return until the aml-cluster compute has four active nodes: **NO**
    3. If the code creates a new aml-cluster compute target, it may be preempted due to capacity constraints: **YES**
    4. The aml-cluster compute target is deleted from the workspace after the training experiment completes: **NO**
30. **YES**
31. **NO**
32. Answer:
    1. Summarize Data
    2. Execute Python Script
33. **YES**
34. Answer:
    1. `pandas as df`
    2. `map[ProductCategoryMapping]`
35. Azure Notebooks
36. **YES**
37. **NO**
38. Replace using Probabilistic PCA
39. Split Data
40. Register the Azure blob storage containing the bird photographs as a datastore in Azure Machine Learning serice
41. **YES**
42. A.
```json

{
    "Name": "DataScientist",
    "IsCustom": true,
    "Description": "Project Data Scientist role",
    "Actions": ["*"],
    "NotActions":[
        "Microsoft.MachineLearningServices/workspaces/*/delete",
        "Microsoft.MachineLearningServices/workspaces/computes/*/write",
        "Microsoft.MachineLearningServices/workspaces/computes/*/delete",
        "Microsoft.Authorization/*/write"
    ],
    "AssignableScopes":[
        "/subscriptions/<id>/resourceGroups/ml-rg/providers/Microsoft.MachineLearningServices/workspaces/ml-ws"
    ]
}

```
43. **NO**
44. **YES**
45. Answer:
    1. k-fold
    2. 3
    3. data
46. Relative Expression Split
47. Answer:
    1. Run code to submit the experiment: the ds-workstation compute instance
    2. Run the training script: the gpu-cluster compute target
48. Answer:
    1. resource_group
    2. subscription_id
49. Answer:
    1. Splitting mode: Split rows
    2. Fraction of rows in the first output dataset: 0.75
    3. Randomized split: True
    4. Stratified split: True
50. A, B and C
51. Answer:
    1. Partition or sample mode: Assign to Folds
    2. (Checkd) Use replacement in the partitioning
52. A, B, C  and D (same B and D)
53. Answer:
    1. Estimator: Tensorflow
    2. Training compute: 12 vCPU, 112 GB memory, 680 GB SSD, 2 GPU, 24 GB GPU memory
54. Answer:
    1. Acces the contents of store1 by using the Azure Machine Learning SDK for Python: Regenerate the keys of account1
    2. Preview the contents of store1 by using Azure Machine Learning studio: Update authentication for store1
55. Answer:
    1. Testing: Local web service
    2. Production: Azure Kubernetes Services (AKS)
56. Answer:
    - Generate a public/private key pair
    - Add the public key to the Git account
    - Clone the Git repository by using an SSH repository URL
57. C. backfill