# Code for Deep Learning for Fashion: Performance Evaluation of Random Forests and CNNs for Fashion Image Classification

This project classifies the Fashion-MNIST dataset using Random Forest and Convolutional Neural Network models. A random forest classifier was initially used as a first attempt model, which, after several tuning parameters, achieved a maximum accuracy of around 87.80\%. However, because of the inefficiency in feature extraction, the attention was diverted to CNNs for better performance. Multiple CNN models were developed, which ranged in complexity from simple single layer CNN networks to complex models that used convolutional layers, dropout, and learning rate adjustment. By making use of the TensorFlow and Keras libraries, the CNN models were highly improved, with the final model reaching a high increase resulting in a test accuracy of 93.72\%. Proper preprocessing of the data were conducted including normalization and EDA. Model performances were evaluated using accuracy, precision, recall, F1 score, and confusion matrices. This study has been informed by insights on architectural enhancement and optimization strategies highlighted in the tutorial  TenserFlow Keras(https://www.tensorflow.org/tutorials/keras/classification). It also highlights the effectiveness of CNNs in image classification tasks and underscores their capability to address the limitations of traditional machine learning approaches. 
## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Required Python libraries (e.g., TensorFlow, Keras, etc.)

## Steps to compile the project

1. Download cnn_model_v4.h5. Save the downloaded file to a directory of your choice on your local system.
2. Download main.py.
3. Update the Path to the model in main.py i.e : loaded_model = tf.keras.models.load_model(model_path). Replace 'model_path' with the actual path to the model file you downloaded in Step 1. 
4. Run the Code
Once the model path is correctly set, you can run the code by executing the main.py file.

## Results

The following results were obtained from the model analysis:

![image](https://github.com/user-attachments/assets/4448e902-fb6f-4c32-ba73-848bb8d19aee)

![image](https://github.com/user-attachments/assets/bcf1143f-ea9e-404e-a094-7b28dc634dc5)

