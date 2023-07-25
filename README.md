# 🧠 TensorFlow MNIST Digit Classifier 🧠
A simple and efficient neural network model to classify handwritten digits using TensorFlow and the MNIST dataset (soon I will implement the image classification part, slow motion is better than no motion).

## 📌 Features
- Simple Neural Network: Built using TensorFlow's Keras API for ease of use.
- Data Normalization: Pre-processes the MNIST dataset for optimal training.
- Dropout Layer: Helps prevent overfitting to improve model generalization.
- Softmax Activation: Converts the model's output logits to probabilities.

## 🚀 Getting Started
1. Clone the repo:
```bash
git clone [https://github.com/reecebaileyy/Image-Classification.git]
cd Image-Classification
```
2. Install TensorFlow:
```bash
pip install tensorflow
```
3. Run the script:
```bash
python image_classification.py
```

## 📈 Model Architecture
- Input Layer: Flattens the 28x28 pixel images.
- Hidden Layer: 128 neurons with ReLU activation.
- Dropout Layer: 20% dropout rate.
- Output Layer: 10 neurons for each digit (0-9).

## 📊 Model Performance
After training for 5 epochs, you can evaluate the model's performance on the test dataset. The accuracy metric will give you an idea of how well the model is performing.

## 🔜 Coming Soon
Custom Image Prediction: Soon, you'll be able to input your own handwritten digit images, and the script will predict the digit for you!

## 🤝 Contributing
Feel free to fork the repository, make changes, and submit pull requests. All contributions are welcome!
