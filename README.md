This project uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras to detect human emotions from facial expressions in color (RGB) images. It supports real-time image prediction and classifies emotions such as happy, sad, angry, surprised, and more.

🧠 Emotions Detected
The model is trained to detect the following emotions:

😠 Angry

🤢 Disgusted

😨 Fearful

😀 Happy

😐 Neutral

😢 Sad

😲 Surprised

📊 Model Training (Optional)
Dataset used: FER-2013

Converted grayscale dataset to RGB by duplicating channels

Augmented using rotation, zoom, flip

CNN architecture: Conv2D + MaxPooling + Dropout + Dense

📌 Requirements
Python 3.x

TensorFlow

NumPy

Matplotlib

Pillow (PIL)
