# 🎧 Audio Classification Using CNNs

Audio Classification Project with Convolutional Neural Networks (CNNs)

---

## 📌 Project Overview

This project demonstrates how to classify audio files using Convolutional Neural Networks (CNNs). Since raw audio signals are one-dimensional and CNNs are highly effective with image data, we first convert audio files into spectrogram images. These images visualize the frequency spectrum over time and serve as the input for our deep learning model.

The trained model can distinguish different audio classes based on learned patterns from spectrograms, providing an efficient and accurate approach to sound recognition.

---

## 🚀 Features

✅ Converts audio files to spectrogram images
✅ Trains a deep learning CNN for audio classification
✅ Achieves high accuracy by leveraging image-based analysis of sound
✅ Clear visualization of spectrograms and model performance

---

## 🛠️ Technologies Used

* **Python 3.x**
* **TensorFlow / Keras**
* **Librosa** - Audio processing and feature extraction
* **Matplotlib** - Visualizing spectrograms
* **NumPy**
* **Scikit-learn** - Evaluation metrics

---

## 🔬 Project Workflow

1. **Data Collection & Preprocessing**

   * Load audio files
   * Normalize audio signals
   * Generate spectrogram images

2. **Dataset Preparation**

   * Organize spectrograms as image dataset for CNN

3. **Model Building & Training**

   * Design CNN architecture
   * Train model on spectrogram dataset
   * Validate model with test data

4. **Evaluation**

   * Accuracy, loss metrics
   * Confusion matrix
   * Visual inspection of model predictions

---

## 🎼 Example Spectrogram

Below is an example of a spectrogram generated from an audio file, which is used as input for the CNN:

<p align="center">
  <img src="https://github.com/Sayed-Hossein-Hosseini/Audio_Classification_Using_CNNs/blob/master/Spectrogram.jpg">
</p>
---

## 📁 Project Structure

```
├── Audio_Classification_Using_CNNs.ipynb   # Main Jupyter Notebook
├── dataset/audio                           # Raw audio files
├── dataset/spectrograms                    # Generated spectrogram images
└── README.md
```

---

## 💡 Future Improvements

* Expand dataset for better generalization
* Experiment with advanced CNN architectures
* Explore real-time audio classification applications

---

## ⚙️ How to Run

1. Launch the Jupyter Notebook:

```bash
jupyter notebook Audio_Classification_Using_CNNs.ipynb
```

2. Follow the notebook cells step by step.

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

**Author:** Sayyed Hossein Hosseini DolatAbadi
