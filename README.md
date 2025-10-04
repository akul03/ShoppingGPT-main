

````markdown
# 🧠 ShopSense AI

**ShopSense AI** is a lightweight, LLM-powered shopping assistant that helps users find products, ask questions, and get personalized recommendations using Google’s Gemini model and RAG.

---

## ⚙️ Setup
```bash
git clone https://github.com/yourusername/ShopSenseAI.git
cd ShopSenseAI
pip install -r requirements.txt
python -m venv venv && source venv/bin/activate
````

Create a `.env` file with:

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

* 🧠 Google Gemini-powered conversations
* 🔍 Smart product + policy search (SQLite + FAISS)
* 💬 Simple Flask web interface

---

## 📜 License

MIT License © 2025 ShopSense AI

```

