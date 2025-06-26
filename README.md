# smart-sorting-transfer-learning-for-identifying-rotten-fruits-and-vegetables

---

# 🍎 Smart Sorting: Rotten vs Fresh Fruit & Vegetable Classification Using Transfer Learning

Smart Sorting is a lightweight deep learning web application that classifies fruits and vegetables as **fresh** or **rotten** across 16 categories. It uses **transfer learning** with **MobileNetV2** and a modern **Flask** backend to deliver fast and accurate predictions in real time.

---

## 🧠 About the Project

This system helps automate the classification of produce images to support smarter food packaging, reduce post-harvest waste, and enhance quality control in agriculture and retail.

It can identify:

* 🟢 **Fresh Produce** (Apple, Banana, Tomato, etc.)
* 🔴 **Spoiled Produce** (Rotten Apple, Rotten Tomato, etc.)

---

## 🚀 How It Works

1. **Upload** an image of a fruit or vegetable.
2. The app uses **deep learning** to analyze the image.
3. A **prediction** (fresh/rotten + class name) is returned, along with a confidence score and image preview.

---

## ✅ Key Features

* 🔍 **Classifies 16 produce types** (8 fresh + 8 rotten)
* ⚙️ **Transfer learning** with MobileNetV2 for optimized speed and accuracy
* 🫼 Built-in **OpenCV image preprocessing**
* 💻 **Flask web interface** with real-time feedback
* 🎨 Clean, modern **HTML/CSS-based frontend**
* 📷 Inline **image preview** for visual confirmation

---

## 🛠 Tech Stack

| Layer         | Technologies                    |
| ------------- | ------------------------------- |
| Model         | TensorFlow / Keras, MobileNetV2 |
| Backend       | Python, Flask                   |
| Preprocessing | OpenCV                          |
| Frontend      | HTML5, CSS3                     |

---

## 🧪 Run It Locally

Follow these steps to run the app on your machine:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/SmartSortingApp.git
cd SmartSortingApp
```

### 2️⃣ Set Up Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate       # For Windows
# source venv/bin/activate  # For macOS/Linux
```

### 3️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

### 4️⃣ Start the Flask Server

```bash
python app.py
```

Then, open your browser at:
👉 **[http://127.0.0.1:5000](http://127.0.0.1:5000)**

---

## 📁 Project Structure

```
SmartSortingApp/
│
├── dataset/
│   ├── train/
│   └── test/
├── model/
│   ├── fruit_classifier.h5
│   └── class_indices.json
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Overview

* **Total Images**: 32,769
* **Classes**: 16 (8 fresh + 8 rotten types)
* **Split**:

  * `dataset/train/`
  * `dataset/test/`

> Sample class indices:

```json
{
  "freshapples": 0,
  "freshbanana": 1,
  ...,
  "rottentomato": 15
}
```

---

## 🧠 Model Insights

* **Model**: MobileNetV2 (fine-tuned)
* **Accuracy**: \~95%
* **Loss**: Low, optimized via tuning and augmentation
* **Saved As**: `fruit_classifier.h5`

---

## 🎯 Real-World Impact

The solution targets a common issue in food supply chains — the inability to quickly identify spoiled produce. Smart Sorting provides:

* ✅ Automated quality checks via image
* ✅ Real-time assistance to vendors, farmers, and retailers
* ✅ Reduced food waste and higher consumer safety

---

## 👥 Contributors

* **Karapakula Balaji Sai Vrushadree**
* **D Bhanu Prakash**
* **K Bhanu Prakash**
* **Tappeta Chinna Sanjamma**

---

## 📬 Contact

For feedback or collaboration, reach out at:

📧 **[kbsv2004@gmail.com](mailto:kbsv2004@gmail.com)**
🔗 [LinkedIn – Sai Vrushadree](https://www.linkedin.com/in/sai-vrushadree-715012255/)
