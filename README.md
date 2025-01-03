# Mine-Detection-Using-Sonar-Data-and-Principal-Component-Analysis

### Description:  
This project focuses on developing a machine learning model to distinguish between underwater mines and rocks using sonar data. The ultimate goal is to improve the safety of submarine navigation through a minefield by maximizing the detection accuracy of mines. The project includes the following tasks:

1. **Data Analysis and Preprocessing**: 
   - Analyze the sonar dataset (`sonar_all_data_2.csv`) containing 60 time samples for each observation.
   - Apply Principal Component Analysis (PCA) to reduce dimensionality and evaluate the importance of each principal component in the classification task.

2. **Model Development**:
   - Train and test a Multi-Layer Perceptron (MLP) neural network classifier (`MLPClassifier`) to distinguish between mines and rocks.
   - Experiment with 1 through 60 principal components to identify the optimal number that maximizes test accuracy.
   - Tune hyperparameters like hidden layers, activation functions, and learning rates to improve performance.

3. **Performance Evaluation**:
   - Compute and print the accuracy for each number of principal components.
   - Plot the relationship between the number of components and test accuracy.
   - Generate a confusion matrix for the results with the highest accuracy to assess false positives, false negatives, and overall prediction performance.

4. **Reporting and Analysis**:
   - Document the maximum accuracy achieved and the corresponding number of principal components.
   - Write a conclusion discussing the results, the shape of the accuracy plot, and the role of PCA in improving classification performance. 
   - Reflect on survival chances in a real minefield and discuss the parameters chosen for the MLPClassifier.

The deliverables include a well-documented Python script (`proj2.py`), accuracy results for each number of components, a confusion matrix, a plot of accuracy versus components, and a detailed report in `proj2.pdf`.
