# Hyper Parameter Optimization of Decision Tree 
Performed classification on the diabetics dataset. Used one of the most Popular classification technique which is Decision Tree to classify wether a person has diabetes or not has diabetes. After implementing a decsion tree using the Sci Kit learn package it had 69% accuracy. Hyper performanced the decion tree using various parametrs like max depth,Criterion etc to increase the accuracy to 77%.
## Hyper Paramter Optimization Using Random Search.
1)First we will adjust the maximum depth parameter. This indicates how deep the decision tree can be. This is know as prunning the decision tree so that it does not overfit the data. We usually keep the maximum depth as 6.

2)Second we will fine tune the min_samples_fit which represents the minimum number of samples required to split an internal node. It ranges between 10% to 100%. If we increase it to 100% which is 10 then the model will underfit.

3)Thirdly we have a parameter by name min_sample_leaf this describes the minimum number of samples to be a leaf Node. IF we increase the parameter by a large extent it causes underfit of the model.

4)Max_features = The number of features to be looking for the best split
If “auto”, then max_features=sqrt(n_features).

If “sqrt”, then max_features=sqrt(n_features).

If “log2”, then max_features=log2(n_features).

If None, then max_features=n_features .
