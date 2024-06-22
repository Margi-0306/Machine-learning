# K-Nearest Neighbors (KNN)

**KNN (k-nearest neighbors)** is a supervised machine learning technique used for both classification and regression tasks. It is primarily used to find the nearest neighbors for a given data point in our dataset. The parameter k is a hyperparameter that specifies the number of neighbors to consider.

## How KNN Works:

1. **Training Phase**

- KNN does not have an explicit training phase where a model is built. Instead, it simply stores the training data.
  
2. **Prediction Phase**

 - For a new data point, calculate its distance to all points in the training set using a chosen distance metric (e.g., Euclidean distance).
 - Select the k points in the training set that are closest to the new data point based on the calculated distances.
   
## Classification:
- **Voting Technique**:
Each of the 𝑘 nearest neighbors "votes" for their class.
The class with the highest frequency (most votes) among the k neighbors is assigned to the new data point.

## Regression:
- **Averaging Technique**:
For regression, the output value for the new data point is the average of the values of its k nearest neighbors.

## Key Features:
**Hyperparameter k**: Determines the number of neighbors to consider. The choice of 𝑘 affects the model's performance. A smaller can lead to overfitting, while a larger can lead to underfitting.


**Distance Metric**: The distance metric (e.g., Euclidean, Manhattan) determines how distances between data points are calculated.
