# Information-Retrieval

This project applies **Information Retrieval** techniques to retrieve visually and semantically similar T-shirt images using the **CLIP model** (Contrastive Language–Image Pre-training) from Hugging Face. It was developed as part of an academic data mining project.

---

## 📂 Dataset

The dataset contains images of T-shirts categorized by type, color, and pattern.

- 📦 Source: [Kaggle – Applied Data Mining Final Project: T-Shirt Data](https://www.kaggle.com/datasets/danizo/applied-data-mining-final-project-t-shirt-data)

---

## 🧠 Model

- Utilized the **CLIP model** (pre-trained) via Hugging Face Transformers.
- Extracted embeddings for T-shirt images and performed similarity-based retrieval using cosine distance.

---

## 🎯 Objective

Given a query T-shirt image, retrieve the **top visually/semantically similar items** from the dataset using vector-based similarity search.

---

## 💡 Results

- The notebook outputs visual results: for each query image, the most similar images are displayed.
- Results are based on **embedding similarity**, not traditional classification.

---

## 🛠 Technologies Used

- Python
- CLIP (via Hugging Face 🤗)
- NumPy, PIL
- Matplotlib
- Cosine Similarity

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install dependencies (see below).
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/danizo/applied-data-mining-final-project-t-shirt-data) and place it in the working directory.
4. Run the notebook (`.ipynb`) in Jupyter or Google Colab.

### 🧩 Requirements

You can install dependencies using pip:

```bash
pip install transformers torch torchvision matplotlib numpy pillow
