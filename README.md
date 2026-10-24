Brain Tumor Detection Using Deep Learning

Project Overview
This project focuses on classifying brain MRI images into four categories using deep learning and transfer learning techniques. The aim is to understand how pre-trained convolutional neural networks can be used for medical image classification.

Models Used
Four pre-trained models are explored and compared:

- VGG16
- VGG19
- ResNet101
- DenseNet121

Dataset
The project uses a brain MRI image dataset containing four classes:

- Glioma
- Meningioma
- No Tumor
- Pituitary

The images are resized to 224 × 224 pixels before being processed by the models.

Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Kaggle Notebooks

Methodology
1. Load and prepare the MRI image dataset.
2. Resize images and preprocess them for the selected model.
3. Divide the training data into training and validation sets.
4. Use transfer learning with pre-trained models.
5. Train a classification layer on top of the pre-trained model.
6. Evaluate the models on a separate testing dataset.
7. Visualize training performance and evaluate classification results.

Project Files
The repository contains separate Jupyter notebooks for the four models:

- `vgg16_beginner.ipynb`
- `vgg19_beginner.ipynb`
- `resnet101_beginner.ipynb`
- `densenet121_beginner.ipynb`

How to Run
1. Open the required notebook in Kaggle or Jupyter Notebook.
2. Set up the brain MRI dataset and update the dataset path if needed.
3. Install the required libraries if they are not already available.
4. Run the notebook cells in order.
5. Review the evaluation results and visualizations.

Learning Objectives
Through this project, I explored:

- Image preprocessing for deep learning
- Training and validation data separation
- Transfer learning using pre-trained CNN models
- Multi-class image classification
- Model evaluation and performance visualization

Future Improvements
- Compare the performance of all four models using verified evaluation results.
- Experiment with data augmentation and hyperparameter tuning.
- Develop a simple web application for image classification.
- Explore additional deep learning architectures.

Disclaimer
This project is for educational purposes only. It is not intended to replace professional medical diagnosis.

Author
Aditi Prasad

AI/ML Undergraduate Student
