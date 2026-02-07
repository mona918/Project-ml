# Project-ml
Using knn algorithm 
# Fashion MNIST Classification using K-Nearest Neighbors (KNN)

## Project Overview
This project implements the K-Nearest Neighbors (KNN) algorithm from scratch to classify images from the Fashion-MNIST dataset. The main goal is to understand how KNN works and how different values of K affect the accuracy of classification.

No machine learning libraries like scikit-learn are used for implementing the algorithm.

## Dataset
The Fashion-MNIST dataset contains grayscale images of size 28×28 pixels representing 10 different types of clothing items.

Classes included in the dataset:
- T-shirt/top
- Trouser
- Pullover  etc..

Each image is converted into a 784-dimensional feature vector.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Algorithm
K-Nearest Neighbors (KNN) is a supervised learning algorithm that classifies data based on the majority class among its K nearest neighbors. Euclidean distance is used to measure the distance between data points.

The model is tested with different K values to find the best accuracy.

## Project Structure
knn_project/
- knn.ipynb
- dataset/
- report.txt
- README.md

## How to Run
1. Download or clone the project folder
2. Open Jupyter Notebook
3. Open the file knn.ipynb
4. Run all cells one by one

## Results
The model achieves an accuracy between 85% and 90% depending on the value of K. A graph is plotted to show the relationship between K values and accuracy.

## Conclusion
This project demonstrates the working of the KNN algorithm and its application to image classification. It also shows how the choice of K value impacts model performance.

## Author
Sonakshi Maharana
