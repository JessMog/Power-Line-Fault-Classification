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
        
## Overall objective:                                          
Detection and classify faulty power transmission lines based on the analysis of current and voltage

A good fault detection system provides an effective, reliable, fast and secure way of a relaying operation. The application of a pattern recognition technique could be useful in discriminating against faults or disturbances and healthy electrical power systems. This will enable the power system to remain in stable condition. 

The analysis  also enables us to differentiate among three phases which phase is experiencing a fault for quick resolution.

## Specific objectives:         

- Which type of fault appears the most,is it line to line or line to ground?
- How can we identify and mitigate the risks associated with power faults?
- Which phase has the most fault?
- What is most likely to cause fault?
  
## Business Success Criteria
- Detecting  power faults and ways to restore it before a blackout happens and affects consumers in homes or offices.
- Find ways to reduce restoration costs. 
- Providing a good model with an accuracy of 90-95%.

## Resources
On this project, there’s a team of four Data Scientists who are working hand in hand with the mentors to critique and evaluate the project. The dataset we are working with “Electric Fault detection and classification” is from the Kaggle website. 

We are also using Github to host our project once it is completed. We have also incorporated Jira as our project management tool.
We shall work with several python libraries, ie, numpy for general tasks, pandas for data manipulation, Scikit learn  for machine learning and matplotlib and seaborn for visualizations. We shall implement supervised learning with python while using models like logistic regression decision trees, KNN and SVM. 




