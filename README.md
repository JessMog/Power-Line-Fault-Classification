# Power-Line-Fault-Classification
Supervised Machine Learning Techniques and Artificial Neural Networks
## Overview
The main objective of our Project is to Detect and classify the faults on electrical power transmission lines using supervised and unsupervised machine learning models. We use a multi-layer perceptron as our base model. 
To reduce the duration of outages and minimize response time to major faults, and to optimize reliability of supply, it is inevitable for power transmission companies such as GRIDco to search for a low-cost communicating device with low power consumption that will relay accurate fault information at real-time back to the control center.
The three phase currents and voltages of one end are taken as inputs in the proposed scheme.

A detailed analysis using 8 different supervised models has been performed to validate the choice of the MLP model. The simulation results concluded that the present method based on the neural network is efficient in detecting and classifying the faults on transmission lines with satisfactory performances. The different faults are simulated with different parameters to check the versatility of the method. 

## Approach
We aim to come up with a machine learning model that can effectively analyze our data and detect whether a power line is faulty or otherwise.
We have two datasets for this,the detection dataset and the classification dataset.
The detection dataset is used to detect whether a line is faulty or otherwise with regards to the amount of current and voltage present, while classification dataset is used to classify where the actual fault is.eg whether the fault is symmetrical or asymmetrical.



## Dataset Description

This project has been sourced from Kaggle. While the dataset for fault detection has 12001 observations and 9 columns, the dataset to be used for classification has 7861 entries and 10 columns.
The detect dataset has 9 columns namely
'Output (S)', 'Ia', 'Ib', 'Ic', 'Va', 'Vb', 'Vc', 'Unnamed: 7
While classification dataset has 10 columns namely
['G', 'C', 'B', 'A', 'Ia', 'Ib', 'Ic', 'Va', 'Vb', 'Vc'], dtype='object'
The detect dataset is used to detect whether a phase is faulty with regards to current and voltage of a single phase,while classification dataset is used to classify where the actual fault lies eg if its between line to ground or line to line.

