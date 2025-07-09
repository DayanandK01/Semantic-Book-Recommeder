# 📚 Semantic Book Recommender

The **Semantic Book Recommender** is a web-based application that uses **natural language understanding** to recommend books based on user-input descriptions, emotional tone, and category preferences.

Built with:
- 🧠 [LangChain](https://www.langchain.com/)
- 🤗 [Hugging Face Transformers](https://huggingface.co/)
- 🎨 [Gradio](https://www.gradio.app/)
- 🐍 Python

---

## 🚀 Features

- 🔍 **Semantic Search**: Find relevant books from your dataset using sentence embeddings.
- 🎭 **Emotion-Based Filtering**: Refine recommendations based on tone (e.g., Happy, Suspenseful).
- 🧩 **Category-Based Selection**: Filter by genre like Fiction, History, etc.
- 🌐 **Interactive Web UI**: Clean Gradio interface for input and results.

---

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/semantic-book-recommender.git
cd semantic-book-recommender
```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Linux/Mac
   venv\Scripts\activate.bat     # On Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. python semantic_book_app.py
  ```bash
  python semantic_book_app.py
  ```
5. Click on the local host link (ctrl + click)
6. 
7. This opens a gradio dashboard and then try below example

🌈 Example Use Case
Input a prompt like:

"A heartwarming story about friendship and overcoming fears"

Then choose:

Category: Fiction

Tone: Happy

And you’ll get visual book recommendations with titles, authors, and short descriptions.
   
