CS 6375.003 Machine Learning
Assignment 3: Neural Networks
Group Memebers:
Swapna Chintapalli - SXC18048
Pallavi Pandey - PXP17009

Car Evaluation Dataset: http://archive.ics.uci.edu/ml/machine-learning-databases/car/car.csv

Compilation Steps:
1. Open NeuralNet.py in Python IDE.
2. Copy car.csv dataset to python project.
3. Run NeuralNet.py file and check console for output.

How to work with other activation functions:
By default Sigmoid activation function is used.
If you want to check other activation functions then change activation_func = "tanh" (or "ReLu") in neural_network.train() and neural_network.predict() at lines 269 and 270.
 
How to work with other dataset:
Copy the required dataset to current Python project.
Change dataset name in NeuralNet() at Line 268.