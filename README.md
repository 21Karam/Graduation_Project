# 🎨 Application of Deep Generative Models for Style Transfer

## 📌 Overview
This project explores and implements deep generative models for artistic style transfer and image generation. It combines multiple approaches including Neural Style Transfer (NST), Fast Neural Style Transfer (FNST), and CycleGAN to transform images and videos into artistic styles.

The system allows transforming real-world images into artistic representations (e.g., Monet style), colorizing grayscale images, and generating new visual styles.

---

## 🧠 Models Used
- Neural Style Transfer (VGG19-based)
- Fast Neural Style Transfer (real-time)
- CycleGAN (unpaired image-to-image translation)

---

## ⚙️ Technologies
- Python
- PyTorch
- TensorFlow / TensorFlow Hub
- OpenCV
- FFmpeg

---

## 📂 Dataset
The dataset consists of:
- **Train A:** 1000 images  
- **Train B:** 1004 images  

Used for unpaired image-to-image translation in CycleGAN.

⚠️ Due to large size, dataset is not included in this repository.

---

## 📥 Download Resources
- Weights: https://drive.google.com/file/d/1wHigwNyTHD2NyJpOOnu0NlleN-gZm8dY/view?usp=drive_link
- Dataset: https://drive.google.com/file/d/1KNDyRPFvIuBhKKr1QrbLWHIx_pdq3sj2/view?usp=drive_link
- Interface: https://drive.google.com/drive/folders/1XqRcCPmcA0Zru0e9QjBx8Z-9hsxhRmrQ?usp=drive_link
  
After downloading, place them like this:
project/
│
├── code/
├── interface/
├── weight/
├── Data/



---

## 🚀 How to Run

1. Download weights and dataset from links above  
2. Place them in the correct folders  
3. Run: interface/interface.ipynb



---

## 🧪 Experiments & Results
- Achieved high-quality artistic style transfer using NST with controllable parameters (α, β)
- Improved output quality with increased iterations (up to 20,000 iterations)
- Reduced artifacts using Total Variation Loss
- CycleGAN successfully learned:
  - Monet-style transformation
  - Grayscale ↔ Color conversion
  - Moiré style generation

---

## ⚡ Key Features
- Supports image and video style transfer
- Real-time processing using Fast NST
- Works without paired datasets (CycleGAN)
- Multi-style generation system

---

## 📊 Evaluation
- PSNR (Peak Signal-to-Noise Ratio)
- SSIM (Structural Similarity Index)
- Visual (Human) Evaluation

---

## 🔮 Future Work
- Increase dataset size for better accuracy
- Train on more styles and domains
- Improve computational efficiency
- Apply to real-time applications (mobile / AR)

---

## 👨‍💻 Authors
- Karam Khziem  
- Laith Suleiman  

---

## 📚 References
Based on research papers in:
- Neural Style Transfer (Gatys et al.)
- Fast NST (Johnson et al.)
- CycleGAN (Zhu et al.)


