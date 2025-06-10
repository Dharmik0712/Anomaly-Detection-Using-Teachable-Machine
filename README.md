# 🧐 Anomaly Detection Using Teachable Machine & Streamlit

[![Streamlit App](https://img.shields.io/badge/Launch%20App-Streamlit-brightgreen?logo=streamlit)](https://anomaly-detection-using-teachable-machine-25jha2ypjf7mfxud7kc5.streamlit.app/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This project demonstrates a lightweight and intuitive **anomaly detection system** using a **Teachable Machine-trained TensorFlow model** deployed with a **Streamlit web app**. The app detects whether a given product image is **Normal** or **Defective** based on a custom-trained model.

---

## 🔍 Project Overview

* ✅ Built and trained a TensorFlow model using [Teachable Machine](https://teachablemachine.withgoogle.com/)
* ✅ Used a custom image dataset of manufactured products with two classes: `Normal` and `Anomaly`
* ✅ Deployed a user-friendly interface using Streamlit
* ✅ Bonus: Integrated **real-time anomaly detection via webcam**

---

## 🚀 Live Demo

🔗 **Try the App Live**
👉 [Streamlit Web App](https://anomaly-detection-using-teachable-machine-25jha2ypjf7mfxud7kc5.streamlit.app/)

---

## 🧪 How It Works

1. Upload an image (`.jpg`, `.jpeg`, `.png`)
2. The image is resized and preprocessed
3. The TensorFlow model predicts whether it's **Normal** or **Anomalous**
4. *(Bonus)* Option to enable your **camera** and get real-time predictions

---

## 🛠️ Tech Stack

* **Frontend/UI**: Streamlit
* **Model**: TensorFlow (Exported from Teachable Machine)
* **Languages**: Python 3.10+
* **Libraries**: `tensorflow`, `numpy`, `opencv-python`, `PIL`

---

## 🧑‍💻 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Dharmik0712/Anomaly-Detection-Using-Teachable-Machine.git
cd Anomaly-Detection-Using-Teachable-Machine
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3. Install dependencies

> 📌 Note: Use Python 3.10 or 3.11 for TensorFlow compatibility.

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
.
├── app.py                     # Main Streamlit App
├── model.h5                   # Trained TensorFlow model
├── requirements.txt           # Python dependencies
├── assets/
│   ├── upload_mode.png        # UI screenshot (optional)
│   └── camera_mode.png        # UI screenshot (optional)
└── README.md
```

---

## 🔧 Training Model (Teachable Machine)

1. Go to [Teachable Machine](https://teachablemachine.withgoogle.com/)
2. Select **Image Project → Standard Image Model**
3. Create two classes: `Normal` and `Anomaly`
4. Upload training images for both classes
5. Train the model
6. Export the model as **TensorFlow (.zip)** and convert to `.h5` using Keras or unzip and use directly

---

## 📌 Requirements

* Python 3.10 or 3.11
* TensorFlow 2.13.0 or compatible
* Streamlit 1.33.0

---

## 📣 Note

If you are using **Python 3.12+**, downgrade to 3.10 or 3.11 for TensorFlow compatibility or update the TensorFlow version in `requirements.txt`.

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 🛣️ Acknowledgements

* [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)
* [Streamlit](https://streamlit.io/)
* TensorFlow Team

---

## 👤 Author

**Dharmik Sompura**
[GitHub Profile](https://github.com/Dharmik0712)
