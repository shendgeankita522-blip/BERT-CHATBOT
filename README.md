# 🤖 BERT Chatbot using Streamlit

<div align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?style=for-the-badge&logo=streamlit)
![BERT](https://img.shields.io/badge/BERT-NLP-yellow?style=for-the-badge)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-orange?style=for-the-badge)

### 💬 Intelligent Question Answering Chatbot using BERT and Streamlit

</div>

---

# 📌 Project Overview

This project is an AI-powered chatbot built using **BERT (Bidirectional Encoder Representations from Transformers)** and **Streamlit**.

Instead of simple keyword matching, the chatbot converts user questions into semantic embeddings using the pretrained **BERT Base Uncased** model and compares them with predefined questions using **Cosine Similarity**.

The chatbot returns the most relevant answer based on the similarity score.

---

# 🚀 Features

✅ Beautiful Streamlit Interface

✅ BERT-based Sentence Embeddings

✅ Cosine Similarity Matching

✅ Predefined Intelligent Responses

✅ Fast Response Generation

✅ Easy to Customize

✅ Background Image Support

---

# 🛠 Technologies Used

- Python
- Streamlit
- Hugging Face Transformers
- BERT Base Uncased
- PyTorch
- Scikit-Learn
- Base64

---

# 📂 Project Structure

```
BERT-Chatbot/
│
├── bert_chatbot.py
├── requirements.txt
├── README.md
├── BG IMAGE.png
```

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/BERT-Chatbot.git
```

Move into project folder

```bash
cd BERT-Chatbot
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Streamlit

```bash
streamlit run bert_chatbot.py
```

---

# 💡 How It Works

1. User enters a question.
2. BERT converts the sentence into an embedding.
3. Stored questions are already converted into embeddings.
4. Cosine Similarity compares user input with stored questions.
5. The closest matching question is selected.
6. Corresponding answer is displayed.

---

# 💬 Sample Questions

- What is your name?
- What is AI?
- What is Data Science?
- What is BERT?
- What is Microsoft Azure?
- Tell me a joke.
- What is your use?

---

# 📊 Workflow

```
            User Question
                   │
                   ▼
        BERT Tokenizer
                   │
                   ▼
      BERT Embedding Generation
                   │
                   ▼
      Cosine Similarity Matching
                   │
                   ▼
     Best Matching Question Found
                   │
                   ▼
        Display Response
```

---

# 📈 Future Improvements

- Voice Input
- Voice Output
- Chat History
- Database Integration
- OpenAI API Support
- Gemini API Integration
- Multiple Language Support
- Better UI Design

---

# 👩‍💻 Author

**Ankita Shendge**

AI & Data Science Enthusiast

📧 LinkedIn:
https://linkedin.com/in/shendgeankita

💻 GitHub:
https://github.com/shendgeankita522-blip

---

# ⭐ Support

If you like this project,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

<div align="center">

### 🌟 Learning today, building intelligent solutions for tomorrow.

</div>
