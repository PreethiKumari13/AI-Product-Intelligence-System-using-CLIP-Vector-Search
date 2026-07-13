# 🛍️ AI Product Intelligence System using CLIP & Vector Search

An AI-powered product intelligence system built using OpenAI's CLIP model for multimodal understanding of product images and text. This project demonstrates three important e-commerce AI capabilities:

- 🔹 Smart Product Recommendation
- 🔹 Product Catalog Deduplication
- 🔹 Reverse Product Search (Text → Image)

This project was developed as part of a Generative AI Bootcamp assignment and demonstrates the use of multimodal embeddings for real-world e-commerce applications.

---

## 🚀 Features

### 1. Smart Product Recommendation
- Recommends complementary products instead of only visually similar ones.
- Example:
  - **Input:** Running Shoes
  - **Recommendations:** Sports Socks, Fitness Watch, Water Bottle

### 2. Product Catalog Deduplication
- Detects duplicate and near-duplicate products using image embeddings.
- Helps maintain a clean product catalog.

### 3. Reverse Product Search
- Users can search using text.
- Example:
  - **Input:** "Blue Casual Shirt"
  - Returns the most relevant product images.

---

## 🛠️ Technologies Used

- Python
- OpenAI CLIP (ViT-B/32)
- Transformers
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Pillow
- Kaggle Notebook

---

## 📂 Project Structure

```
AI-Product-Intelligence-System/
│
├── Product_Intelligence_Homework.ipynb
├── Report.pdf
├── README.md
└── screenshots/
```

---

## ⚙️ Workflow

```
Product Images + Product Text
             │
             ▼
      CLIP Embeddings
             │
             ▼
   Similarity Computation
             │
   ┌─────────┼─────────┐
   ▼         ▼         ▼
Recommendation  Deduplication  Reverse Search
```

---

## 📊 Results

The notebook demonstrates:

- Product recommendations using CLIP embeddings.
- Duplicate product detection.
- Text-to-image product retrieval.
- Visualization of recommendation results.

---

## 📁 Dataset

**Fashion Product Images (Small)**

The dataset contains fashion product images along with metadata used for multimodal search and recommendation.

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook in Jupyter or Kaggle.
4. Attach the Fashion Product Images (Small) dataset.
5. Run all notebook cells.

---

## 🎯 Future Improvements

- Deploy as a Streamlit web application.
- Add FAISS for faster vector search on large datasets.
- Integrate an LLM for natural language product recommendations.
- Support image-to-image product search.

---

## 👩‍💻 Author

**Preethi Kumari**

GitHub: https://github.com/PreethiKumari13

---

⭐ If you found this project useful, consider giving it a star!
