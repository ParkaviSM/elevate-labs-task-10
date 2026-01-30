
Handwritten Digit Classification using KNN (MNIST)

This project demonstrates handwritten digit classification using the K-Nearest Neighbors (KNN) algorithm on the MNIST dataset.
It is implemented in Python using Scikit-learn and Matplotlib as part of an internship / academic machine learning task.

📌 Project Objective

Understand distance-based classification

Apply KNN algorithm on image data

Perform K-value tuning

Visualize model performance and predictions

📂 Dataset

Dataset Name: MNIST (Modified National Institute of Standards and Technology)

Samples: 70,000 grayscale images

Image Size: 28 × 28 pixels

Features: 784 pixel values per image

Labels: Digits from 0 to 9

Dataset source: OpenML (mnist_784)

🛠️ Tools & Libraries Used

Python 🐍

Scikit-learn

NumPy

Matplotlib

Google Colab / Jupyter Notebook

🧪 Steps Performed

Load MNIST dataset using fetch_openml

Inspect dataset shapes (X and y)

Visualize sample digit images

Split dataset into training and testing sets

Apply StandardScaler (important for KNN)

Train KNN classifier with K = 3

Experiment with multiple K values (3, 5, 7, 9)

Plot Accuracy vs K

Generate Confusion Matrix

Display test images with predicted labels

📊 Results

Achieved high classification accuracy on test data

Identified optimal K value using accuracy comparison

Visualized misclassifications using confusion matrix

Successfully predicted handwritten digits from unseen data

📈 Accuracy vs K Plot

The project includes a graph showing how accuracy changes with different K values, helping to select the optimal K for the model.

🧩 Confusion Matrix

A confusion matrix is generated to analyze:

Correct classifications

Misclassified digits

Model strengths and weaknesses

🖼️ Sample Predictions

The notebook displays sample test images along with their predicted digit labels to demonstrate final model output.

📁 Repository Structure
├── task_10.ipynb
├── README.md

🎓 Learning Outcome

By completing this task, the intern gains:

Practical understanding of KNN

Knowledge of feature scaling importance

OUTPUTS 

<img width="548" height="192" alt="Image" src="https://github.com/user-attachments/assets/585c91f6-993e-4a0f-8bb8-4d04727c4f53" />

<img width="477" height="342" alt="Image" src="https://github.com/user-attachments/assets/a8d906b9-33d0-45f2-adea-a892a63b9ee9" />

<img width="448" height="393" alt="Image" src="https://github.com/user-attachments/assets/f7044c6f-3c1b-46c2-9244-30375a417284" />

<img width="569" height="203" alt="Image" src="https://github.com/user-attachments/assets/0ed0a8b0-e398-432f-bc90-d30a5921bcdf" />


Experience in model evaluation & tuning

Confidence in handling real-world image datasets# elevate-labs-task-10
