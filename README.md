# Facial Emotion Detection 

This project is a **Facial Emotion Recognition (FER)** system built and trained on a custom Convolutional Neural Network (CNN) for emotion classification.. It detects human emotions from facial expressions in an image upload. The interface is built using **Gradio**, making it easy to interact with the model in a web app format.

---

## 📂 Dataset

We use the **[FER2013 Emotion Detection Dataset](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer)** from Kaggle. It contains 35,887 grayscale images (48x48 pixels) categorized into 7 emotions.

**Emotions Detected:**

* 😠 Angry
* 🤢 Disgust
* 😨 Fear
* 😄 Happy
* 😢 Sad
* 😲 Surprise
* 😐 Neutral

---

## 🧠 Model Summary

* Built and trained a custom Convolutional Neural Network (CNN) for emotion classification.
* Achieved an **F1 Score of 0.62** on the validation set.
* The model was trained using image preprocessing and data augmentation techniques to improve generalization.

---

## 📊 Results

* **F1 Score**: `0.62`
* Performs reasonably well for most common emotions like *happy*, *sad*, and *neutral*.
* More training or data cleaning might help improve *disgust* and *fear* classifications.

---

## 🔍 Confusion Matrix
The confusion matrix below shows the model's performance across all 7 emotion classes.

![image](https://github.com/user-attachments/assets/97376189-5c29-4142-a25a-a27e488e6c51)


