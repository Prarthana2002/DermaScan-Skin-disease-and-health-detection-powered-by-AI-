# DermaScan - (Skin-disease-and-health-detection-powered-by-AI)

This project uses a Convolutional Neural Network (CNN) to classify skin disease images into 7 categories: Acne, Alopecia Areata, Melasma, Pigment, Vitiligo, Warts, and Wrinkle. The model was trained on a labeled image dataset and built using TensorFlow/Keras.

📁 Dataset
Images of skin diseases categorized into 7 classes:

acne (0)
alopecia_areata (1)
melasma (2)
pigment (3)
vitiligo (4)
warts (5)
wrinkle (6)


📊 Model Summary
The model is a CNN with:

3 convolutional layers with batch normalization and max pooling

Flattening layer

Fully connected dense layer with dropout

Final dense output layer with softmax activation

🧪 Key Features
Image preprocessing and augmentation

Model training and evaluation

Prediction on single image with display of image and class label

Achieves accurate classification for multiple skin conditions

🔧 Requirements
Python 3.x
TensorFlow
NumPy
Matplotlib
OpenCV

Install using:
pip install tensorflow numpy matplotlib opencv-python

🚀 How to Run
Clone the repo:

git clone https://github.com/Prarthana2002/DermaScan-Skin-disease-and-health-detection-powered-by-AI.git
cd DermaScan

Train the model or load existing model.

Run prediction using:
predict_single_image('path_to_image.jpg')

📷 Output Example
![capture_1745055529556](https://github.com/user-attachments/assets/3eff7942-94d6-4c10-abcb-69a9351719c1)

![capture_1745055507372](https://github.com/user-attachments/assets/4e59b32e-af88-4755-8079-1858ca8efb18)

![capture_1745055411016 2](https://github.com/user-attachments/assets/dc916455-1200-4d82-8c30-d89cecc03646)

![capture_1745055355076](https://github.com/user-attachments/assets/07c08600-9c51-49dd-8f7c-917d56e91d91)
