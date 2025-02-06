# Smart_Dermatology_with_Deep_Learning

Skin diseases affect millions globally, often requiring expert diagnosis that may not be readily available, especially in underserved regions. This project leverages deep learning to develop an automated system for classifying various skin diseases using image analysis. The model aims to assist healthcare professionals by reducing the diagnostic burden and improving early detection.
Features

•	Deep Learning-Based Image Classification: Utilizes Convolutional Neural Networks (CNNs) to classify skin diseases.

•	Large Dataset Processing: Handles over 40,000 images across 10 skin disease categories.

•	Efficient Data Storage: Uses MongoDB for storing model predictions and metadata.

•	Interactive Web Application: Built with Streamlit for real-time user interaction.

•	Scalable Processing: Apache Spark is used to process large-scale image datasets.

•	Data Visualization: Power BI provides insights into model accuracy and performance.

### Tech Stack

•	Deep Learning Framework: TensorFlow, Keras

•	Big Data Processing: Apache Spark

•	Database: MongoDB

•	Visualization: Power BI

•	Web App: Streamlit

### Dataset

•	Source: Kaggle - Skin Disease Dataset

•	Preprocessing: Images resized, normalized, and augmented (rotation, flipping, scaling, etc.).

•	Data Splitting: Training, validation, and test sets for model evaluation.

### Model Development

•	Implemented CNNs for feature extraction and classification.

•	Trained using TensorFlow with optimizations such as dropout and batch normalization.

•	Monitored accuracy, precision, recall, and F1-score throughout training.

•	Model Performance: 2,000 Images - 16.03% | 5,000 Images - 36.56% | 100,000 Images - 56.10% Accuracy.

•	Power BI is used to analyze model accuracy, confusion matrices, and learning curves.

![image](Skin_Disease_Image.jpg)
