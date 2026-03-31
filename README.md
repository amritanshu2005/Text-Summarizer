# 🚀 Text Summarizer using FastAPI & Transformers

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Framework-green)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![License](https://img.shields.io/badge/License-MIT-orange)

---

## 🌟 Overview

This project is a **Text Summarization API** built using **FastAPI** and Hugging Face's **T5 Transformer model**. It converts long text into concise and meaningful summaries using modern NLP techniques.

---

## ✨ Features

* ⚡ Fast and scalable API using FastAPI
* 🧠 Abstractive summarization with T5 model
* 🔌 Simple REST API for easy integration
* 📄 Handles large text inputs efficiently
* 🪶 Lightweight and clean implementation

---

## 🧠 Tech Stack

* **Python**
* **FastAPI**
* **Transformers (Hugging Face)**
* **PyTorch**
* **Uvicorn**

---

## 📂 Project Structure

```
Text_Summarizer/
│── app.py
│── index.html
│── requirements.txt
│── .gitignore
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/amritanshu2005/Text-Summarizer.git
cd Text-Summarizer
```

### 2️⃣ Create virtual environment

```
python -m venv venv
.\venv\Scripts\activate   # Windows
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```
python -m uvicorn app:app --reload
```

Open in browser:
👉 http://127.0.0.1:8000

---

## 📡 API Usage

### Endpoint: `/summarize`

### Request:

```json
{
  "text": "Enter your long text here..."
}
```

### Response:

```json
{
  "summary": "Generated summary..."
}
```

---

## ⚠️ Notes

* First run may take time (model download)
* Recommended Python version: **3.10 / 3.11**
* Avoid Python 3.13 for better compatibility

---

## 🔮 Future Improvements

* Add frontend UI (React / HTML)
* Deploy on cloud platforms (Render / AWS)
* Optimize model inference speed
* Add authentication & rate limiting

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Amritanshu Chaudhary**

---

⭐ If you like this project, consider giving it a star!
