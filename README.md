# denoising-autoencoder-fashion
Denoising Autoencoder using deep learning to remove noise from fashion product images. Built with TensorFlow/Keras and trained on a Kaggle dataset. Includes reconstruction results and performance evaluation.
# 🧠 Denoising Autoencoder for Fashion Product Images

## 📌 Project Description

This project implements a **Denoising Autoencoder** using deep learning techniques to remove noise from fashion product images. The model is trained to reconstruct clean images from noisy inputs, demonstrating the capability of neural networks in image restoration tasks.

---

## 📊 Dataset

* **Fashion Product Images Dataset**
* Source: Kaggle (Param Aggarwal)
* Total Images: ~44,000

---

## ⚙️ Methodology

1. **Data Preprocessing**

   * Images resized and normalized
   * Dataset loaded using Python and OpenCV

2. **Noise Addition**

   * Gaussian noise added to input images
   * Simulates real-world noisy conditions

3. **Model Architecture**

   * Convolutional Autoencoder
   * Encoder: Extracts features
   * Decoder: Reconstructs clean image

4. **Training**

   * Loss Function: Mean Squared Error (MSE)
   * Optimizer: Adam

5. **Evaluation**

   * Reconstruction error measured using MSE
   * Visual comparison of:

     * Original Image
     * Noisy Image
     * Denoised Output

---

## 📈 Results

* The model successfully removed noise from images
* Achieved low reconstruction error
* Generated visually clear outputs

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* OpenCV
* Matplotlib

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Run the training script or open the notebook:

```bash
python train.py
```

---

## 📷 Output

| Original | Noisy | Denoised |
| -------- | ----- | -------- |
| ✔️       | ✔️    | ✔️       |



---

## 📌 Conclusion

This project demonstrates how deep learning models like autoencoders can effectively learn image representations and remove noise. It highlights the importance of feature extraction and reconstruction in computer vision tasks.

---

## 🔗 Dataset Link

https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset

---

## 👩‍💻 Author

Mansi Adarsh
