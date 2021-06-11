# Normalization and Deep learning architectures

## Objective
Build three architectures with:
* Network with Group Normalization
* Network with Layer Normalization
* Network with L1 + BN

## Approach

The base architecture considered is from [assignment 6](https://github.com/EVA6-Group-15/discover-architectures/blob/master/ParamsLessThan8k/MNIST_99_4_Iter06_ReducedParam.ipynb). 

The excel sheet with calculations is located [here](./notebooks/Normalizations.xlsx)

![Excel sheet](images/excel_sheet.png)

### Model 1: Network with Group Normalization
<br>

![Summary - Group Normalization](./images/group_norm.png)



**Result: Misclassified images** 

<br>

![Misclassified images - Group Normalization](./images/gn_incorrect.png)


### Model 2: Network with Layer Normalization

<br>

![Summary - Layer Normalization](./images/layer_norm.png)



**Result: Misclassified images** 

![Misclassified images - Layer Normalization](./images/ln_incorrect.png)

### Model 3: Network with L1 + BN 

<br>

![Summary - L1 + Batch Normalization](./images/batch_norm.png)



**Result: Misclassified images** 
![Misclassified images - L1 + Batch Normalization](./images/bn_incorrect.png)
## Plots

### Test/Validation Loss

![Validation](./images/loss_summary.png)


### Test/Validation Accuracy

![Validation](./images/acc_summary.png)


## Analysis

* In the validation accuracy plot, we observe that the accuracy of the model with batch norm is highest compared to the other two techniques. 
* 




