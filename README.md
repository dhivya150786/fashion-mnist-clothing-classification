# Fashion MNIST Clothing Classification using Neural Network

##  Project Overview

This project implements a **Neural Network for clothing image classification** using **TensorFlow and Keras**.

The model is trained on the **Fashion-MNIST dataset** to classify clothing images into 10 different categories, such as **T-shirts, trousers, dresses, shirts, sneakers, and ankle boots**.

The project was developed and executed using **Google Colab**.

## Objective

To build and train a simple Dense Neural Network that can classify Fashion-MNIST clothing images with a **test accuracy of at least 80%**.

##  Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab
* Fashion-MNIST Dataset

##  Dataset

The **Fashion-MNIST** dataset is loaded directly using TensorFlow/Keras.

It contains grayscale images of clothing items with a size of **28 × 28 pixels**.

### Classes

The dataset contains 10 clothing categories:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

##  Neural Network Architecture

The project uses a simple Dense Neural Network:

```text
Input Image (28 × 28)
        ↓
Flatten Layer
        ↓
Dense Layer (128 neurons, ReLU)
        ↓
Dense Layer (10 neurons, Softmax)
        ↓
Predicted Clothing Class
```

### Model Details

* **Input:** 28 × 28 grayscale image
* **Flatten:** Converts the image into a 1D array
* **Hidden Layer:** 128 neurons with ReLU activation
* **Output Layer:** 10 neurons with Softmax activation
* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Training Epochs:** 10
* **Validation Split:** 10%

##  Project Workflow

1. Import TensorFlow, NumPy and Matplotlib.
2. Load the Fashion-MNIST dataset.
3. Define the 10 clothing classes.
4. Display a sample clothing image.
5. Normalize image pixel values.
6. Build the Dense Neural Network.
7. Compile the model.
8. Train the model for 10 epochs.
9. Evaluate the model on test data.
10. Predict the clothing class of a test image.
11. Plot training and validation accuracy.

##  Results

The trained model is evaluated using the Fashion-MNIST test dataset.

**Expected Test Accuracy:** ≥ 80%

The notebook also displays:

* Test accuracy
* Predicted clothing class
* Actual clothing class
* Training accuracy
* Validation accuracy graph

> **Note:** The exact test accuracy may vary slightly depending on the training run.

##  Sample Prediction

The model predicts the clothing category of a test image and compares it with the actual label.

Example:

```text
Predicted: Sneaker
Actual: Sneaker
```

##  Accuracy Visualization

The project includes a graph showing:

* Training Accuracy
* Validation Accuracy

This helps visualize the model's learning performance across the training epochs.

##  How to Run

### Using Google Colab

1. Open the `.ipynb` file in Google Colab.
2. Run the cells sequentially.
3. The Fashion-MNIST dataset will be loaded automatically.
4. Train the model.
5. View the test accuracy and predictions.

### Using Jupyter Notebook

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib
```

Then open:

```text
fashion_mnist_clothing_classification.ipynb
```

##  Author

**Dhivya U**

Computer Science and Engineering Student
