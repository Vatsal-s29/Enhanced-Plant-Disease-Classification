# 🌿 SmartCrop Diagnoser: Lightweight and Interpretable Plant Disease Classification

A state-of-the-art plant disease classification system that combines **transfer learning**, **ensemble learning**, and **explainable AI (XAI)** to deliver **highly accurate and efficient predictions**, tailored for **IoT devices** and **edge computing** environments.

---

## 🚀 Highlights

- ✅ **98.8% Accuracy** with a custom ensemble of MobileNet, EfficientNet, and DenseNet.
- ⚡ **Highly efficient** (45%) model, perfect for **resource-constrained environments**.
- 🧠 **Transfer Learning**: Utilized pretrained models for fast and robust training.
- 🤖 **Ensemble Learning**: Blended predictions from multiple lightweight models for improved generalization.
- 🔍 **Explainable AI**: Integrated **Grad-CAM** to visualize model decisions, enhancing interpretability and trust.
- 📈 **50% Improvement** in ensemble weight optimization using interpretable insights from XAI.

---

## 💡 Why This Project?

Traditional deep learning models are often black-box and computationally expensive. This project is designed to:

- Deliver **high-accuracy disease classification** using low-footprint architectures.
- Enhance **transparency** through XAI techniques.
- Ensure compatibility with **IoT platforms** and **edge computing scenarios** (e.g., smart farms, handheld devices, drones).

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Transfer Learning (MobileNet, EfficientNet, DenseNet)
- Ensemble Learning (Soft voting with optimized weights)
- Grad-CAM (Explainable AI)
- NumPy, OpenCV, Matplotlib

---

## 📊 Performance Metrics

| Model        | Accuracy | Model Size | Inference Time |
|--------------|----------|------------|----------------|
| MobileNet    | 97.2%    | Low        | Fast           |
| EfficientNet | 97.8%    | Medium     | Fast           |
| DenseNet     | 96.5%    | Medium     | Medium         |
| **Ensemble** | **98.8%**| Optimized  | Fast           |

✅ Ensemble achieves **best accuracy** while maintaining **efficiency**, suitable for deployment on edge devices.

---

## 🔍 Grad-CAM Visualizations

Grad-CAM is used to highlight which parts of the plant leaf the model is focusing on when making predictions.

<p align="center">
  <img src="path_to_sample_gradcam_image_1.png" width="300"/>
  <img src="path_to_sample_gradcam_image_2.png" width="300"/>
</p>

---

## 🌐 Real-world Applications

- Smart Farming with IoT
- Mobile-based disease detection for farmers
- Edge AI in drones and agricultural sensors

---

## 📁 Project Structure

