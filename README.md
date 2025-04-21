# Lane Detection using VGG16-UNet

This project implements a semantic segmentation pipeline using a VGG16-UNet architecture to detect lane lines in road images. It is trained and evaluated using the TuSimple dataset.

## 📌 Project Overview

- Semantic segmentation for lane line detection
- Uses VGG16 as encoder + custom UNet decoder
- Trained on TuSimple dataset (6,000+ annotated images)
- Implemented in TensorFlow and Keras
- Developed and tested on Kaggle/Colab (GPU-enabled)

## 🧠 Model Architecture

The model combines the VGG16 pretrained encoder with a UNet-style decoder using skip connections to preserve spatial features.

![Model Architecture](link-to-diagram-if-added)

## 📁 Files

- `lane_detection_vgg16_unet.ipynb` – Main notebook
- `best_model.keras` – Trained model file (optional)
- `predicted_sample.png` – Example result output

## 🔧 Dependencies

- TensorFlow / Keras
- NumPy, Pandas
- OpenCV
- Matplotlib

## 📊 Results

- ~98% training accuracy
- ~97.5% test accuracy
- Performs well under normal daylight, struggles slightly in occluded or poor lighting scenarios

## 📷 Example Output

![Predicted Lane](link-to-predicted-image)

## 🏁 Future Work

- Incorporate post-processing (curve fitting)
- Train on more diverse datasets (e.g., BDD100K)
- Add real-time video inference

## 🔗 Dataset

- [TuSimple Lane Detection Dataset](https://github.com/TuSimple/tusimple-benchmark)

---

Let me know if you’d like me to:
- Customize this `README.md` with your actual image links  
- Generate a `.gitignore` or license  
- Or help you organize the folder layout (`models/`, `notebooks/`, etc.)

Once done, **share the GitHub repo link** in resumes, reports, or LinkedIn to highlight your work! 🚀

