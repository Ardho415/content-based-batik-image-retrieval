# 👘 Batik Image Retrieval System

A Content-Based Image Retrieval (CBIR) system designed to retrieve visually similar Batik images based on texture features. Instead of relying on image labels or metadata, the system compares visual characteristics extracted directly from the images to find the most relevant matches.

This project demonstrates the application of computer vision techniques for Indonesian cultural heritage preservation through automated Batik image retrieval.

---

## 🚀 Features

- Content-Based Image Retrieval (CBIR)
- Texture feature extraction
- Image preprocessing
- Similarity computation between images
- Top-K similar image retrieval
- Retrieval result visualization
- Performance evaluation

---

## 📂 Project Structure

```
.
├── Batik_Image_Retrieval.ipynb
├── dataset/
├── query_images/
├── retrieval_results/
└── README.md
```

---

## 🧠 Methodology

The retrieval pipeline consists of the following stages:

1. Image Acquisition
   - Load Batik image dataset
   - Select query image

2. Image Preprocessing
   - Resize images
   - Convert color space if required
   - Normalize image data

3. Feature Extraction
   - Extract texture features
   - Generate feature vectors for each image

4. Similarity Measurement
   - Compare feature vectors
   - Compute similarity (or distance) scores

5. Image Retrieval
   - Rank images based on similarity
   - Return Top-K most similar Batik images

6. Visualization
   - Display query image
   - Display retrieved images ranked by similarity

---

## 🛠 Technologies

- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Retrieval Workflow

```
Query Image
      │
      ▼
Image Preprocessing
      │
      ▼
Feature Extraction
      │
      ▼
Feature Vector
      │
      ▼
Similarity Computation
      │
      ▼
Image Ranking
      │
      ▼
Top-K Retrieved Images
```

---

## 📈 Evaluation

The notebook evaluates the effectiveness of the retrieval system by comparing the query image with the Batik image database and ranking images according to their visual similarity.

Example outputs include:

- Query image visualization
- Top-K retrieved Batik images
- Similarity scores
- Retrieval performance analysis

---

## 🎯 Applications

This project can be applied to:

- Batik image search
- Cultural heritage preservation
- Visual product recommendation
- Fashion image retrieval
- Digital museum collections
- Computer vision research

---

## 💡 Future Improvements

- Integrate deep learning feature extraction (CNN, ResNet, EfficientNet)
- Support larger Batik image databases
- Develop a web-based image search interface
- Optimize retrieval speed using FAISS
- Extend to multi-class Batik pattern recognition

---

## 👥 Authors

- Ardho Firdaus
- Team Project
