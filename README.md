# Digit Recognition using CNN

This project is a digit recognition system built using a Convolutional Neural Network (CNN) trained on the MNIST dataset. The model can recognize hand-drawn digits from 0 to 9 and is deployed in Google Colab with an interactive drawing interface.

## Features
- **Pre-trained CNN Model**: Uses a simple convolutional neural network for digit classification.
- **Interactive Drawing Interface**: Allows users to draw digits on a canvas and predict them in real-time.
- **Google Colab Integration**: The project runs in Google Colab, making it easy to use without local setup.

## Technologies Used
- **Python**
- **TensorFlow/Keras**
- **NumPy**
- **Matplotlib**
- **Google Colab**
- **JavaScript (for drawing interface)**

## How It Works
1. **Model Training**:
   - Loads the MNIST dataset.
   - Normalizes the image data.
   - Defines a CNN model with Conv2D, MaxPooling, and Dense layers.
   - Trains the model on the dataset.

2. **Drawing Interface**:
   - Uses JavaScript to create a canvas where users can draw digits.
   - Converts the drawing to a 28x28 grayscale image.
   - Passes the image to the model for prediction.

3. **Prediction**:
   - The trained model processes the image and predicts the digit.
   - Displays the predicted digit using Matplotlib.

## How to Run
1. Open the [Google Colab Notebook](https://colab.research.google.com/).
2. Run all the cells sequentially.
3. Draw a digit on the interactive canvas.
4. Click the **Predict** button to see the recognized digit.

## Installation (For Local Setup)
If you want to run it locally:
```bash
pip install tensorflow numpy matplotlib pillow
```
Clone the repository and run the Jupyter Notebook:
```bash
git clone https://github.com/your-username/Digit-Recognition.git
cd Digit-Recognition
jupyter notebook
```
Open the notebook and run the cells.

## Future Improvements
- Deploying the model as a web application.
- Enhancing model accuracy with more complex architectures.
- Adding more interactive features like erasing and color selection.

## Author
**Vedant Tripathi**

## License
This project is open-source and available under the [MIT License](LICENSE).

