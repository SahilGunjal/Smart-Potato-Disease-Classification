# Potato Disease Classification Project

## Overview
Developed a robust potato disease classification system using artificial neural networks (ANN) with TensorFlow and Keras. The system employs a Convolutional Neural Network (CNN) architecture to accurately categorize potato images into three classes: Early Blight, Late Blight, and Healthy.

## Key Components and Features

1. **Data Processing and Augmentation:**
   - Utilized TensorFlow's image_dataset_from_directory for efficient loading and preprocessing of the potato disease image dataset.
   - Applied data augmentation techniques, including random flipping and rotation, to enhance model robustness.

2. **Neural Network Architecture:**
   - Implemented a CNN with multiple convolutional layers and a fully connected layer.
   - Achieved a remarkable 96.88% accuracy on the test dataset after training over 50 epochs.

3. **Model Deployment:**
   - Deployed the trained model effectively using FastAPI to create a server.
   - Developed user-friendly interfaces for interacting with the model on mobile and web platforms.

4. **FastAPI Integration:**
   - Established endpoints for server operations and predictions, enhancing the system's usability.
   - Ensured seamless communication between the deployed model and user interfaces.

5. **Mobile App and Website Development:**
   - Created a mobile app using React Native for Android and iOS platforms.
   - Developed a responsive website using React and JavaScript.

6. **User-Friendly Interfaces:**
   - Designed interfaces that simplify disease detection for farmers, providing an accessible and intuitive user experience.

7. **Project Impact:**
   - Contributed to agriculture technology by providing an efficient solution for potato disease detection.
   - Enhanced accessibility for farmers through the development of user-friendly applications.

## How to Use

1. **Clone the Repository:**
   ```
   git clone https://github.com/SahilGunjal/Smart-Potato-Disease-Classification.git
   
   ```

2. **Navigate to the Project Directory:**
   ```
   cd Smart-Potato-Disease-Classification
   ```

3. **Run the FastAPI Server:**
   ```
   uvicorn server:app --reload
   ```

4. **Explore the Mobile App and Website:**
   - Open the React Native project in your preferred development environment for mobile app deployment.
   - Host the React website on a server of your choice.
