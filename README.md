# Waste Classification using CNN

## Project Overview
This project aims to develop a Convolutional Neural Network (CNN) model to classify images of plastic waste into different categories. The model helps in automating waste segregation, which can assist in recycling and waste management efforts.

## Dataset
The dataset consists of images of plastic waste, categorized into different types such as:
- PET Bottles
- Polythene Bags
- Hard Plastics
- Others

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn

## Model Architecture
The CNN model consists of:
- Convolutional layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Fully connected layers for classification
- Softmax activation function for multi-class classification

## Training Process
- Preprocessed dataset by resizing and normalizing images.
- Used data augmentation techniques to improve generalization.
- Trained the model using categorical cross-entropy loss and Adam optimizer.
- Evaluated the model using accuracy and confusion matrix.

## Results
- Achieved an accuracy of **[XX]%** on the test dataset.
- The model successfully classifies different types of plastic waste.

## How to Run
1. Clone the repository:
   ```sh
   git clone <repository_link>
   cd waste-classification
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```sh
   python train.py
   ```
4. Test the model:
   ```sh
   python test.py --image <image_path>
   ```

## Future Improvements
- Increase dataset size for better generalization.
- Implement Transfer Learning with pre-trained models like ResNet or MobileNet.
- Deploy the model as a web or mobile application.

## Contributors
- **Madhav**

## License
This project is licensed under the MIT License.

