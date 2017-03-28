# StatisticalLearning
Contains R notebook and detailed explanations of Linear regression models

The contents in these notebooks are based on book **Introduction to Statistical Learning** by:
_Gareth James (Author), Daniela Witten (Author), Trevor Hastie (Author), Robert Tibshirani (Author)_

##Important Points:
1. In case of confusion between _newdata_ and _data_ in predict function please consider this note from ?predict.lm:
     '''
     Variables are first looked for in ‘newdata’ and then searched for in the usual way (which will include the 
     environment of the formula used in the fit).  A warning will be given if the variables found are not of the 
     same length as those in ‘newdata’ if it was supplied.
     '''
