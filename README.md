# Pegasos

This repository contains the implementation of Pegasos algorithm for Support Vector Machine (SVM). The algorithm uses sub gradient method and converts the constraint convex optimiztion problem into unconstrained optmization problem.
Batch gradient descent with random shuffling is used for the implementation of algorithm. The a;gorithm aimed to maximize the dis tance between positive an dnegative hyperplanes and hence increasing the classification accuracy.
This is a jupyter notebook, so just run the cells for training of algorithm and visulazing the results.

Random dataset is created using sklearn make_classification module. distribution of dataset is given below.
![image](https://user-images.githubusercontent.com/111289395/216756559-a813425a-38f6-4a3b-98d5-f349fef27d44.png)

300 iterations are used for the implementation with a batch size of 100 and this is a binary classification problem with learning rate 0.001. The results for implementation are given below
![image](https://user-images.githubusercontent.com/111289395/216756628-09c45cf2-23a7-406e-a7b0-0ecd03b63015.png)

plot of loss Vs Iterations are given below:

![image](https://user-images.githubusercontent.com/111289395/220623653-c592dc7e-bbc2-4cbf-8445-7d28e79e9aa9.png))

