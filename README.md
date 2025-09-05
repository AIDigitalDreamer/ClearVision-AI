# ClearVision-AI
ClearVision AI – A deep-learning powered cataract detection system that analyzes ophthalmic images using convolutional neural networks. It enables rapid, accurate, and remote screening with heatmap-based visual indicators of lens opacity, supporting early diagnosis and reducing the global burden of cataract-related blindness.
## 🚀 How to Run Cataract Detection Model in Colab

Follow these steps to set up and run the project in Google Colab:

### 1️⃣ Open Google Colab
- Go to [Google Colab](https://colab.research.google.com/)  
- Create a **new Python notebook**  

### 2️⃣ Upload the Model File
- Download the pre-trained model from here:  
  👉 [Download cataract_full_model_stage2.keras](YOUR_GOOGLE_DRIVE_LINK)  
- In Colab, click the **folder icon** on the left sidebar  
- Click **Upload** and upload the file `cataract_full_model_stage2.keras`  

### 3️⃣ Get Your Ngrok Auth Token
Ngrok is needed to create a public link for the web app.  

1. Go to [ngrok.com](https://ngrok.com/)  
2. Sign up (free account is enough)  
3. After logging in, go to the **Dashboard → Your Authtoken**  
4. Copy the token (it looks like a long random string)  

### 4️⃣ Paste the Code
Paste the provided Colab code into your notebook.  
👉 Make sure to replace this line with your token:  

```python
NGROK_AUTHTOKEN = "PASTE_YOUR_TOKEN_HERE"
