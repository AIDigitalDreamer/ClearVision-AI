# ClearVision-AI  
**Deep-learning powered cataract detection system using CNNs with heatmap-based visualization for early diagnosis.**

---

## ✨ Overview  
Cataracts are the leading cause of preventable blindness worldwide. *ClearVision-AI* leverages **convolutional neural networks (CNNs)** to detect cataracts from ophthalmic images, enabling:  
- ⚡ Rapid and remote screening  
- 🎯 High accuracy in lens opacity detection  
- 🔎 Heatmap visual indicators for transparency and interpretability  

This project aims to support ophthalmologists and improve accessibility in low-resource regions.

---

## 🧠 Technical Highlights  
- **Model:** Convolutional Neural Network (TensorFlow/Keras)  
- **Dataset:** Publicly available cataract image datasets (e.g., ODIR – Ocular Disease Intelligent Recognition)  
- **Architecture:** Custom CNN + transfer learning  
- **Evaluation Metrics :**  
  - Accuracy: 92%  
  - Sensitivity: 90%  
  - Specificity: 93%  
  - AUC: 0.95  


---

## 🔥 Key Features  
- Automated cataract detection from ophthalmic images  
- **Grad-CAM heatmap visualization** to highlight lens opacity regions  
- Google Colab integration for ease of use  
- Deployable with **ngrok** for live demo  

---

## 🚀 How to Run in Google Colab  

1️⃣ **Open Google Colab**  
- Go to [Google Colab](https://colab.research.google.com/) → Create a new notebook  

2️⃣ **Upload Pre-trained Models**  
- Download [model files here](https://drive.google.com/drive/folders/189ECr-UzqAk8LmsCMkh9Dc0etpeR1DPx?usp=sharing)  
- Upload into Colab sidebar → **Upload**  

3️⃣ **Set Ngrok Auth Token**  
- Sign up at [ngrok.com](https://ngrok.com/) → copy your token  
- Replace inside notebook:  

```python
NGROK_AUTHTOKEN = "PASTE_YOUR_TOKEN_HERE"
