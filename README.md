# PlasticAndOrganicWasteClassification
# CNN Project: Classification of Plastic Waste

This repository contains the code and resources for a deep learning project aimed at classifying images of waste into two categories: **Organic Waste (O)** and **Recyclable Plastic Waste (R)**. The project is part of an internship focused on developing a Convolutional Neural Network (CNN) model to tackle the growing problem of waste segregation.

---

## **Project Overview**

### **Objective**

The goal of this project is to:

- Build a CNN model to classify images of plastic waste into their respective categories.
- Explore preprocessing, visualization, and data augmentation techniques to improve model performance.

### **Dataset**

The dataset consists of approximately 25,000 images divided into training and testing sets. Each set contains images categorized into:

- **Organic Waste (O)**
- **Recyclable Plastic Waste (R)**

The dataset was sourced from Kaggle.

---

## **Work Completed: Week 1**

During the first week, the following tasks were completed:

1. **Data Loading:**

   - Successfully loaded the dataset into memory using Python libraries such as OpenCV and Pandas.

2. **Initial Visualization:**

   - Created a pie chart to visualize the distribution of the two categories: Organic and Recyclable.
   - Displayed random sample images from the dataset to gain an understanding of its content.

3. **Data Exploration:**

   - Analyzed the distribution of image sizes.
   - Examined pixel intensity distributions for potential preprocessing steps.



---


## **Steps in the Project**

1. **Data Loading and Visualization**

   - Load and explore the dataset using libraries like OpenCV and TensorFlow.
   - Visualize image distributions and examples to gain insights into the dataset.

2. **Preprocessing**

   - Resize all images to a uniform shape.
   - Normalize pixel values to the range [0, 1].
   - Convert categorical labels into numerical format.
   - Apply data augmentation techniques to improve model robustness.

3. **Model Development**

   - Design and train a CNN architecture suitable for binary classification.
   - Use evaluation metrics like accuracy, precision, recall, and F1-score to assess performance.

4. **Testing and Evaluation**

   - Evaluate the trained model on the test dataset.
   - Visualize predictions and misclassifications.

5. **Deployment**

   - Explore options for deploying the model for real-time inference.

---

## **How to Use the Repository**

### **Requirements**

- Python 3.8+
- TensorFlow 2.x
- OpenCV
- Matplotlib
- Pandas
- NumPy

Install the dependencies using:

```bash
pip install -r requirements.txt
```

### **Running the Code**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/cnn-plastic-waste-classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd cnn-plastic-waste-classification
   ```

3. Run preprocessing and training scripts:

   ```bash
   python src/data_preprocessing.py
   python src/model_training.py
   ```

---

## **Acknowledgments**

- **Kaggle** for providing the dataset.
- **Mentors** and team members for their support and guidance.

---

## **Contact**

For any questions or suggestions, feel free to reach out:

- **Email**: [your-email@example.com](mailto\:your-email@example.com)
- **GitHub**: [Your GitHub Profile](https://github.com/your-username)


