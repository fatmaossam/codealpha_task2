# codealpha_task2
# Handwritten Digit Recognition

This project implements a **Convolutional Neural Network (CNN)** using TensorFlow to classify handwritten digits from the MNIST dataset. The model is trained to achieve high accuracy in recognizing digits from 0 to 9.

## Features
- Uses the MNIST dataset for training and testing.
- Implements a CNN with the following layers:
  - **Convolutional Layer**: Extracts features from the image.
  - **MaxPooling Layer**: Reduces the spatial dimensions of the image.
  - **Dense Layers**: Classifies the digits.
- Achieves high accuracy on the test dataset.

## Dataset
The MNIST dataset contains:
- 60,000 training images.
- 10,000 testing images.
- Each image is grayscale and has a resolution of **28x28 pixels**.

## Project Structure
- `main.py`: Contains the implementation of the CNN model.
- `model.h5`: Saved model after training (if applicable).
- `README.md`: This file.

## How to Run
1. **Install Required Libraries**:
   ```bash
   pip install tensorflow numpy pillow
   
## How to Train the Model
1. **Install Required Libraries**:
   Make sure you have the necessary libraries installed:
   ```bash
   pip install tensorflow numpy pillow

## Run the Training Script:
To train the model, simply execute the main.py file in your terminal
python main.py

## Training Details
The model is trained on the MNIST dataset for **5 epochs** by default.

### During Training:
For each epoch, the following metrics will be displayed:
- **Loss**: The error rate of the model, indicating how well the model is performing.
- **Accuracy**: The percentage of correct predictions made by the model.

### Evaluate the Model:
After training, the script evaluates the model on the test dataset. The following metrics will be displayed:
- **Accuracy**: Indicates how well the model performs on unseen test data.
- **Loss**: Measures the model's prediction error.

### Example Output:
After the model is trained and evaluated, you might see results like the following:

Epoch 1/5
60000/60000 [==============================] - 2s 35ms/step - loss: 0.2500 - accuracy: 0.9300
Epoch 2/5
60000/60000 [==============================] - 2s 33ms/step - loss: 0.1500 - accuracy: 0.9550
...
Epoch 5/5
60000/60000 [==============================] - 2s 33ms/step - loss: 0.0500 - accuracy: 0.9800

The accuracy is: 0.98
The loss is: 0.05

## Contact
If you have any questions or need further assistance, feel free to reach out:

- **Email**: [fvtma22@gmail.com] 
- **GitHub Issues**: Open an issue on this repository.  
- **LinkedIn**: [https://www.linkedin.com/in/fatma-hossam-987907306/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3Bep15W0J1RHWzcC1rNC9gQQ%3D%3D)





