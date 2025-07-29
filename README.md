# SVM Image Classifier – Cats vs Dogs 🐱🐶

This project implements an image classification model using **Support Vector Machines (SVM)** to distinguish between images of **cats** and **dogs**. It is developed as part of SkillCraft Technology Task 03 to demonstrate classical machine learning techniques applied to computer vision tasks.

## 📁 Dataset

The dataset used is the **Kaggle Cats and Dogs Dataset**, which contains 25,000 labeled images of cats and dogs.
- Dataset link: [Kaggle - Dogs vs Cats](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs)
- Each image is either labeled as `Cat` or `Dog`.

## 🧠 Techniques Used

- Support Vector Machine (SVM) from `scikit-learn`
- Image processing with `OpenCV`
- Grayscale conversion and resizing (50x50)
- Flattening images into 1D feature vectors
- Train-test split for model validation
  
## 🧰 Libraries Used

- Python
- OpenCV
- NumPy
- Scikit-learn
  
## 🛠️ How it Works

1. **Data Preprocessing**  
   - Load images from the directory
   - Convert to grayscale
   - Resize to 50x50 pixels
   - Flatten into 1D array

2. **Model Building**  
   - Use `SVC()` from `sklearn.svm`  
   - Train the model on processed image data

3. **Evaluation**  
   - Accuracy Score  
   - Classification Report
