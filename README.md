# 🧬 AIML-Based Spatial Transcriptomics in Cancer Research
Open the Notebook
You can open the Colab notebook directly:
https://colab.research.google.com/drive/1dHTvorrUWzSoIDrvC_Wy3U8pn52jNzaF?usp=sharing

## 📌 Overview

This project applies **Artificial Intelligence and Machine Learning (AIML)** techniques to analyze **spatial transcriptomics** data in cancer research. The objective is to classify spatial tissue regions as **tumor** or **normal** based on gene expression patterns and image features, enhancing understanding of the tumor microenvironment and aiding biomedical research.

---
🔍 How it works:
We used image patches from tissue samples and extracted deep features using Autoencoders. These were combined with gene expression data to build a graph, where each node represents a tissue patch.
We then applied Graph Neural Networks (GCNs) to model spatial relationships and predict tumor presence, achieving meaningful clustering and tissue classification.

## 🧠 Key Features

- 🔍 **Image Patch Extraction** from tissue sections  
- 🧪 **Data Augmentation** using Albumentations  
- ⚙️ **Autoencoder-based Feature Extraction** using TensorFlow  
- 🧱 **Graph Construction** from spatial coordinates  
- 🔄 **GCN (Graph Convolutional Network)** modeling via PyTorch Geometric  
- 🗂️ **Clustering and Segmentation** of tumor vs. normal regions  
- 📊 **Visualization** of learned representations and spatial clusters  

---

## 🛠️ Technologies Used

- **Python**, **TensorFlow**, **PyTorch**, **Scanpy**, **Albumentations**, **Anndata**
- **Jupyter Notebook (Google Colab)**  
- **PyTorch Geometric**, **scikit-learn**, **Seaborn**, **Matplotlib**

---

🤖 Model Highlights
Autoencoder: Dimensionality reduction for image patch features
GCN Model: Graph-based reasoning using neighborhood gene expression and image embeddings
---

📈 Results
results/Augmented_image.png
Binary classification of tumor vs. normal spatial regions
results/tumorVSnormal_final_output.png
Feature visualization using UMAP/t-SNE
Spatial heatmaps of expression and clustering results
📌 Graphs and outputs are saved in the /results folder.

📚 References
Scanpy Documentation
PyTorch Geometric
Spatial Transcriptomics
10x Genomics Data Portal

📜 License
This project is open-source and available under the MIT License.

Author
Isha Yadav
B.Tech CSE (AIML)
