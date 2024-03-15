# DL
Deep Learning || Neural Network // By: Duarte Patrão and Mariana Pires

The provided code addresses a machine learning problem using a variant of Neural Network models implemented in TensorFlow/Keras, akin to exercises conducted during classes. Specifically, the project aims to alleviate the burden on healthcare professionals by automating the identification of malaria-infected cells through image analysis.

**Data Preprocessing:**
The code loads the malaria dataset using TensorFlow Datasets, preprocesses it by normalizing and resizing images, and splits it into training, testing, and validation sets.
**Model Architecture:** 
It constructs a Convolutional Neural Network (CNN) using TensorFlow's Sequential API. The CNN comprises multiple convolutional and pooling layers, followed by densely connected layers and a final output layer with sigmoid activation.
**Training and Evaluation:**
The model is compiled with appropriate loss function and metrics and trained on the training data while validating on the validation set. Training progress is monitored, and accuracy and loss metrics are visualized using custom plotting functions.

**Automation:**
Automating the detection of malaria-infected cells can significantly reduce the workload of medical professionals, enabling quicker diagnosis and treatment.
**Efficiency:**
Machine learning models can process large volumes of data much faster than humans, potentially leading to more timely and accurate diagnoses.
**Scalability:**
Once trained, the model can be deployed on various platforms, allowing for widespread use and scalability in healthcare settings.

# Objectives:
The primary goal is to develop a machine learning model capable of accurately identifying malaria-infected cells from microscopic images. By automating this process, the model aims to lessen the burden on healthcare professionals, allowing them to focus on more critical tasks.
Quicker and more accurate diagnosis of malaria can lead to better patient outcomes and contribute to the overall improvement of healthcare services.


# Examples:
Furthermore, in this code, the number of epochs used is 10. Below, we showcase a good example of 10 epochs vs 20 epochs.
  - 10 epotchs
![accurary training](https://github.com/MarianaPires93/DL/assets/154060433/820fcc63-8ba1-4079-9cc6-fc7c4a80c978)

  - 20 epotchs
![accuracy gone wrong](https://github.com/MarianaPires93/DL/assets/154060433/c2a28b9f-129e-4de1-9cd2-b33388171e5a)

It is clear that with 20 epochs, overfitting starts to occur. To prevent further issues, it is advisable to run the code with 10 epochs for a better accuracy model.


**Example of Prediction:**
![predictions](https://github.com/MarianaPires93/DL/assets/154060433/bc22c022-178b-456e-a109-6a517d91a6b9)

The code runs successfully.



