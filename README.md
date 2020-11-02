# Federated Learning using Neural Network with Stochastic Gradient Descent Optimizer
The experiment simulated Federated Learning using 8 Virtual Workers to classify mHealth Activity dataset using Neural Network with Stochastic Gradient Descent Optimizer which the dataset recorded by sensors. Federated Learning is modern concept in machine learning provides a new breakthrough in the data training process. If machine learning processes training data centrally, federated learning provides sharing of trained models from multiple devices (workers).
Federated learning focuses on protecting the privacy of highly sensitive personal data, so the user does not need to upload data to the data center in the modeling process. However, each device trains its own model locally and then all the models are aggregated into a new model.
# Requirements
- python
- pytorch
- syft


# Dataset
We provided mHealth Acivity in CSV format, the dataset contains 21 features, and 6 classes.
The features consist of:
- Column 1: acceleration from the chest sensor (X axis)
- Column 2: acceleration from the chest sensor (Y axis)
- Column 3: acceleration from the chest sensor (Z axis)
- Column 4: acceleration from the left-ankle sensor (X axis)
- Column 5: acceleration from the left-ankle sensor (Y axis)
- Column 6: acceleration from the left-ankle sensor (Z axis)
- Column 7: gyro from the left-ankle sensor (X axis)
- Column 8: gyro from the left-ankle sensor (Y axis)
- Column 9: gyro from the left-ankle sensor (Z axis)
- Column 10: magnetometer from the left-ankle sensor (X axis)
- Column 11: magnetometer from the left-ankle sensor (Y axis)
- Column 12: magnetometer from the left-ankle sensor (Z axis)
- Column 13: acceleration from the right-lower-arm sensor (X axis)
- Column 14: acceleration from the right-lower-arm sensor (Y axis)
- Column 15: acceleration from the right-lower-arm sensor (Z axis)
- Column 16: gyro from the right-lower-arm sensor (X axis)
- Column 17: gyro from the right-lower-arm sensor (Y axis)
- Column 18: gyro from the right-lower-arm sensor (Z axis)
- Column 19: magnetometer from the right-lower-arm sensor (X axis)
- Column 20: magnetometer from the right-lower-arm sensor (Y axis)
- Column 21: magnetometer from the right-lower-arm sensor (Z axis)
- Column 22: Label (0 for the null class)

 The labels of activity consist of:
- L1: Standing still (1 min) 
- L2: Sitting and relaxing (1 min) 
- L3: Lying down (1 min) 
- L4: Walking (1 min) 
- L5: Climbing stairs (1 min) 
- L6: Running (1 min)

# References
- https://blog.openmined.org/federated-learning-additive-secret-sharing-pysyft/
- https://www.simonwenkel.com/2019/07/20/introduction-to-pysyft.html
- https://blog.openmined.org/upgrade-to-federated-learning-in-10-lines/
