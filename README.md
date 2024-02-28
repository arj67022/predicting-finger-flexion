# predicting-finger-flexion
Predicting Finger Flexion using electrocorticography (ECoG) data

# Overview
This work was completed as a final project in BE 521: Brain-Machine Interface at the University of Pennsylvania. In this project, finger flexion were predicted using electrocorticography (ECoG) data from three patients. The algorithm used involved the following steps:

- pre-processing: The ECoG signals were first passed through digital filters
- Features were identifed through a literature study and then extracted from the data
- Various ML models were fit on the data, but the best performing model was a ridge regression model
- Minor post-processing steps

The final model had a correlation of 0.5182 on testing data. 