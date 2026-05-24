# Face Recognition using PCA and ANN (MLP)

## Introduction

The current project deals with the implementation of **Face Recognition System** that uses **Principal Component Analysis (PCA)** and **Artificial Neural Network (ANN / MLP Classifier)** algorithms on the **Labeled Faces in the Wild (LFW)** dataset. The idea behind this system is to automatically detect human faces from the input image using PCA for dimensionality reduction and feature extraction and further recognize their identities using the multi-layer perceptron artificial neural network. The implementation also includes the visualization of Eigenfaces and comparison between predicted and real names of people.

---

## Working

1. Loading the LFW dataset containing multiple images of different celebrities using the command `fetch_lfw_people()`.
2. Preprocessing the images, dividing them into training and testing datasets with split ratio 80:20.
3. Dimensionality reduction via Principal Component Analysis where 180 principal components (Eigenfaces) are generated.
4. Feeding the extracted PCA components to the multi-layer perceptron classifier for further classification.
5. Using the trained neural network for predicting the identities of input images.
6. As the final output displaying the following elements:

   * Input Eigenfaces
   * Recognized faces
   * Predicted name
   * Real name
   * Prediction probability

---

## Highlights

1. Implementation of the **dimensionality reduction technique – PCA** for reducing dimensionality and extracting facial features.
2. Visualization and generation of **Eigenfaces** which represent dominant facial elements like eyes, nose, etc.
3. Application of the highly advanced **Artificial Neural Network (ANN/MLP Classifier)** with multiple hidden layers `(512, 256)`.
4. Processing more than **1200+ faces** from the LFW dataset containing multiple individuals.
5. Reducing the complexity of computations significantly by reducing thousands of pixel features to **only 180 components**.
6. Fast and effective face recognition process using optimized MLP with Adam optimization algorithm.
7. Showing one image from each class with prediction probability values.

---

## Results

1. Total number of facial images in the processed dataset: **1288**

2. Total number of classes recognized: **7 people/celebrities**

3. Number of PCA components generated: **180**

4. MLP/ANN used in the implementation:

   * Number of hidden layers: `(512, 256)`
   * Activation function: `ReLU`
   * Optimization algorithm: `Adam`

5. Dataset split ratio:

   * Training data: **75%**
   * Testing data: **25%**

6. Achieving total face recognition accuracy of **around 85-92 percent** depending on the dataset split.

7. Confidence rate for predicting the identities of faces ranges from **75 to 99 percent**.

---

## Technologies Used

* Python Programming Language
* Scikit-learn Machine Learning Library
* NumPy Data Science Package
* Matplotlib Visualization Toolkit
* PCA
* ANN / MLPClassifier

---

## Applications

1. Surveillance systems
2. Biometric systems for authentication purposes
3. Attendance systems in the offices/organizations
4. Criminal identification systems
5. Access control systems
6. Human computer interface applications
7. Social media photo tagging systems
## Future Scope

1. Integrating **Deep Learning models** such as Convolutional Neural Networks (CNNs) to improve recognition accuracy further.
2. Expanding the system to support **real-time face recognition** using live webcam or CCTV video streams.
3. Implementing **face detection and tracking** for surveillance and security applications.
4. Deploying the model as a **web or mobile application** for practical real-world usage.
5. Combining PCA with advanced techniques like **LDA, Autoencoders, or Transfer Learning** for improved feature extraction.
6. Adding anti-spoofing mechanisms to detect fake faces or photographs for secure biometric authentication.
7. Optimizing the system for faster processing on low-power devices such as embedded systems and IoT platforms.
8. Extending the project toward multi-modal biometric systems by combining face recognition with fingerprint or iris recognition techniques.
