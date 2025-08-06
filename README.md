# 📚 ShelfSense
---

## 🔍 Overview

`ShelfSense` is not your average book recommendation system. Unlike traditional recommenders that rely on keyword matches, filters, or popularity scores, `ShelfSense` uses **semantic search** and **emotional tone detection** to deliver book recommendations that truly understand your intent — and adapt to your *mood*.

---

## 💡 What Makes It Unique?

### 🧠 Goes Beyond Metadata  
Most recommenders depend on genres, ratings, or popularity. `ShelfSense` understands your input **in natural language** and searches by *meaning*, not just tags.

> _Query Example:_  
> “A dark, twisty thriller that questions reality.”

### 🎭 Emotion-Aware Filtering  
Select your current mood — Happy, Suspenseful, Angry, etc. — and the model adjusts results based on **emotional embeddings** in the book summaries.

### 🔍 Semantic Matching  
Uses **HuggingFace sentence embeddings** to match user queries with book descriptions at a conceptual level using vector search.

### 📚 Clean, Responsive UX  
Built with **Gradio**, the app displays:

- Book thumbnails  
- Smartly formatted author names  
- Concise descriptions for each result

---

## 🚀 Try It Out

Run the full app in Colab with **one click**:
 
🔗 [Launch in Google Colab](https://colab.research.google.com/drive/1AHAL1F7naaSqCJY8GsWPAsN7F96SFDJX)
> Uses `launch(share=True)` for remote access.


![phone-app](https://github.com/user-attachments/assets/62ae20ee-a9f2-4957-beab-0b04ff8e6611)

Mobile Application view

<img width="1860" height="818" alt="Screenshot (421)" src="https://github.com/user-attachments/assets/e2c89233-b8fb-4dc3-bd96-5e2124f0c482" />

Desktop Application View

---

## 🛠️ Tech Stack

| Area           | Tools Used                         |
|----------------|------------------------------------|
| UI             | Gradio                             |
| NLP Embeddings | HuggingFace Transformers           |
| Vector Search  | FAISS + LangChain                  |
| Backend Logic  | Python, Pandas                     |
| Dataset        | ~1,000 books with emotion scores   |

---

## 🧠 How It Works

1. **Embed Book Descriptions**  
   All book summaries are converted into semantic vectors using HuggingFace models.

2. **Semantic Search with FAISS**  
   User queries are embedded and compared to the dataset using vector similarity.

3. **Emotion & Genre Filtering**  
   Results are scored and re-ranked based on the selected emotional tone and genre.

4. **Display Results**  
   Shows rich outputs with title, author, image, and short summary using Gradio.

---

## 🎯 Use Case

> “You’re feeling anxious and want a calming story about hope and healing.”  
> ShelfSense gets it.  
> Traditional recommenders? Not really.

---

## 🔮 Future Enhancements

- Add user profiles + collaborative filtering  
- Live sentiment analysis from Goodreads or Amazon reviews  
- Upgrade to React or Streamlit for production-grade UI  

---

## 🤖 Why This Project Matters

- Showcases modern NLP techniques with **real user-facing value**
- Bridges **emotion understanding** with **semantic relevance**
- Combines multiple AI tools into a **polished, functioning product**

---
