# 📝 Feature Extraction from Text using BERT

A machine learning and deep learning project for extracting meaningful features from text data using **BERT embeddings**, followed by **K-Means clustering** for grouping similar text samples. This project demonstrates how transformer-based models can help with unsupervised text understanding.

---

## 🌟 Features

- ✍️ Extracts **contextual embeddings** from text using **pretrained BERT**  
- 📊 Groups texts using **K-Means clustering**  
- 📈 Achieved **Silhouette Score = 0.66**, indicating strong cluster cohesion  
- 🧪 Supports evaluation of cluster quality and embedding visualization  
- 🔁 Modular pipeline: text preprocessing → embedding → clustering → evaluation

---

## 🧠 Model Info

- ✅ **Embedding Model:** BERT (from Hugging Face Transformers)  
- 📌 **Clustering Algorithm:** K-Means  
- 📉 **Evaluation Metric:** Silhouette Score (0.66)  
- 📄 Input: Raw text data (.txt)  
- 📤 Output: Data saved into csv file that trained on an algorithm
- Cluster labels for each text entry

---

## ⚙️ Getting Started

### 🔧 To Run Locally:

1. Clone the repo:
git clone https://github.com/Vikas717-creator/text-feature-extraction.git cd text-feature-extraction

markdown
Copy
Edit

2. Install required libraries:
pip install -r requirements.txt

markdown
Copy
Edit

3. Run the pipeline:
python text_preprocessing.py python bert_embeddings.py python clustering.py python visualize_clusters.py

yaml
Copy
Edit

---

## 🧪 Example Use Case

- Input: Text samples like reviews, tweets, articles
- Features saved into csv file get trained on an model 
- Output: Clustered groups of semantically similar content

---

## 📊 Technologies Used

- Python  
- Hugging Face Transformers  
- Scikit-learn  
- Pandas / NumPy  
- Matplotlib / Seaborn  
- NLTK or spaCy *(for preprocessing)*

---
## Screenshots
![image](https://github.com/user-attachments/assets/03f19a81-99c5-4ce1-9072-a46a535948bf)
![image](https://github.com/user-attachments/assets/2e553b15-ec82-4469-be4a-793534d15268)
![image](https://github.com/user-attachments/assets/2603fcb6-dfd6-458c-95b5-4d7ac4f8a0f1)



## 🔮 Future Enhancements

- 🔎 Add dimensionality reduction using **t-SNE** or **UMAP**  
- 🧠 Replace K-Means with DBSCAN or Agglomerative Clustering  
- 🌐 Build a simple web interface to upload and cluster text  
- 📊 Add visual dashboards with Streamlit

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss improvements.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🔗 Connect with Me

- GitHub: [@Vikas717-creator](https://github.com/Vikas717-creator)  
- LinkedIn: [Vikas Thakur](https://www.linkedin.com/in/vikas-thakur-2304a6261/)
