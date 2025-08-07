# 🔦 UNET_LENET: Hybrid Deep Learning Model for Low-Light Image Enhancement

This project presents a hybrid deep learning architecture that combines **U-Net** and **LeNet** to enhance low-light images effectively. The model is trained and evaluated on the LOL dataset and integrates denoising, contrast enhancement, and structural preservation for improved image quality.

---

## 🚀 Features

- ✅ Hybrid U-Net + LeNet model for spatial feature extraction and enhancement  
- 🌗 Specially designed for **low-light image enhancement**  
- 📊 Evaluates performance using PSNR, SSIM, and training time  
- 🧠 Includes preprocessing techniques like **Wavelet Denoising** and **CLAHE**  
- 💾 Saves model checkpoints to **Google Drive** every 5 epochs  
- 📈 Visualizes training time per epoch and enhancement performance  

---

## 📂 File Included

- `UNET_LENET.ipynb` — Main notebook containing model definition, training, evaluation, and visualization (Google Colab ready)

---

## 📦 Dependencies

Make sure the following libraries are installed in your Colab environment:

```bash
pip install tensorflow opencv-python pywavelets matplotlib
```

## 📸 Dataset

Uses the **LOL (Low-Light)** dataset:  
The LOL dataset consists of paired low-light and normal-light images, ideal for supervised learning in image enhancement.

---

## 🧪 Evaluation Metrics

The model evaluates output image quality using:

- 📏 **PSNR** – Peak Signal-to-Noise Ratio  
- 🧠 **SSIM** – Structural Similarity Index  
- ⏱️ **Time per Epoch** – For performance analysis

---

## 🧑‍💻 Steps to Use in Google Colab

Follow the steps below to use the notebook in Google Colab:

### 1. Upload the Notebook

- Open [Google Colab](https://colab.research.google.com/)
- Upload `UNET_LENET.ipynb`

### 2. Install Required Libraries

Run the following cell to install dependencies:

```python
!pip install tensorflow opencv-python pywavelets matplotlib
```

### 3. Mount Google Drive

To save model checkpoints:

```python
from google.colab import drive
drive.mount('/content/drive')
```

### 4. Prepare the Dataset

- Download the LOL dataset  
- Upload or move it to your **Google Drive** or **Colab workspace**  
- Adjust the dataset path in the notebook accordingly

---

### 5. Run the Notebook

Execute all cells in order:  
📌 **Model Definition → Preprocessing → Training → Evaluation → Visualization**

---

### 6. Check Results

- Enhanced images and evaluation metrics will be saved or displayed  
- Model checkpoints are saved every **5 epochs** to your Google Drive

---

## 📌 Applications

- 📷 Smartphone or DSLR photo enhancement in low-light  
- 📹 Video surveillance preprocessing for night-time feeds  
- 🩺 Medical imaging in poorly lit environments
