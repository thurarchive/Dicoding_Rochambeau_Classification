# Rochambeau (Rock-Paper-Scissors) Classification Project✨

## Project Overview
This project focuses on classifying images of rock, paper, and scissors using a convolutional neural network (CNN). The goal is to build a robust model that can accurately predict the class of a given image, helping to automate the recognition of these hand gestures in the classic game of Rochambeau (rock-paper-scissors). The project utilizes advanced image processing techniques and machine learning methods to achieve high accuracy.

Key features of this project include:

- Dataset preparation by splitting into training and validation sets
- Image augmentation to improve model generalization
- Implementation of a Sequential model with multiple hidden layers
- Use of an advanced optimizer and loss function to enhance performance
- Achieving a model accuracy of 97% with a stable learning curve
- Interactive prediction capabilities through Google Colaboratory

The project is implemented in Python using TensorFlow and Keras for model development, with data exploration and visualization conducted within Google Colaboratory.

## Submission Criteria
The project fulfills the following submission criteria:

- The dataset used is the **rockpaperscissors** dataset, downloaded via the link: [rockpaperscissors.zip](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip).
- The dataset is split into a training set (60%) and a validation set (40%), resulting in 1,314 training samples and 874 validation samples.
- Image augmentation is applied to the training data to prevent overfitting.
- An image data generator is utilized to feed data into the model.
- A Sequential model is implemented with more than one hidden layer.
- The model training time is kept under 30 minutes.
- The project is executed on Google Colaboratory.
- The model achieves an accuracy of 97%, exceeding the required 85%.
- The model can accurately predict images uploaded to Colab.

## Additional Enhancements
- **Achieved 97% accuracy**: The model was fine-tuned to achieve a high accuracy of 97%, with a stable learning curve throughout the training process.
- **Advanced image augmentation**: Extensive image augmentation techniques were applied to improve model generalization.
- **Custom optimizer and loss function**: A more sophisticated optimizer and loss function were employed to enhance model performance beyond the baseline taught in the course.

## Setup Environment - Google Colaboratory

To set up the environment using Google Colaboratory, follow these steps:

1. **Clone the project repository:**
    ```sh
    !git clone https://github.com/your-repo/rochambeau-classification.git
    cd rochambeau-classification
    ```

2. **Download the dataset:**
    ```sh
    !wget https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip
    !unzip rockpaperscissors.zip
    ```

## Run Model

Once your environment is set up and dependencies are installed, you can run the model training and prediction directly in Colab with the following command:

```sh
# Run the training script
!python train_model.py

# Predict on a new image
!python predict.py --image_path <path_to_image>
```
Copyright © Fajri Fathur Rahman 2024
