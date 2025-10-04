

````markdown
# 🧠 ShopSense AI

**ShopSense AI** is a lightweight AI shopping assistant that helps users find products, ask questions, and get personalized recommendations — powered by **Google Gemini** and **RAG (Retrieval-Augmented Generation)**.

---

## ⚙️ Setup

```bash
git clone https://github.com/yourusername/ShopSenseAI.git
cd ShopSenseAI
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
````

Create a `.env` file with your API key:

```
GOOGLE_API_KEY=your_google_api_key
```

Initialize the database:

```bash
python scripts/init_db.py
```

---

## 🚀 Run

```bash
python app.py
```

Visit **[http://localhost:5000](http://localhost:5000)** to start chatting.

---

## ✨ Features

* 🧠 Conversational AI powered by Google Gemini
* 🔍 Smart product & policy search (SQLite + FAISS)
* 💬 Clean, responsive Flask web interface

---

## 📜 License

**MIT License © 2025 ShopSense AI**

```

---


