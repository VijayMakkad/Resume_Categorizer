# 🧠 Resume Categorizer

A machine learning-powered notebook that classifies resumes into relevant job categories using natural language processing (NLP) techniques. Built with Python and open-source libraries, this project simplifies resume screening for recruiters or HR systems.

---

## 📂 Project Structure

```
resume_categorizer/
├── resume_categorizer.ipynb     # Main Jupyter notebook
├── README.md                    # Project documentation
├── /data                        # Folder to store resume text files or datasets (if used)
└── /models                      # (Optional) Folder to store trained models
```

---

## 🛠️ Features

* **Text Cleaning & Preprocessing:** Removes punctuation, stopwords, digits, and applies lemmatization.
* **Resume Classification:** Uses NLP techniques (TF-IDF) and machine learning models to classify resumes.
* **Category Prediction:** Automatically detects the most relevant category for a given resume.
* **Model Evaluation:** Includes accuracy, confusion matrix, and classification report.

---

## 🧪 Technologies Used

* Python 🐍
* NLTK (Natural Language Toolkit)
* Scikit-learn
* Pandas, NumPy
* Matplotlib & Seaborn (for visualizations)
* Jupyter Notebook

---

## 🚀 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/VijayMakkad/resume_categorizer.git
   cd resume_categorizer
   ```

2. **Install Dependencies**
   Make sure you have Python ≥ 3.8 installed. Then:

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Notebook**

   ```bash
   jupyter notebook resume_categorizer.ipynb
   ```

---

## 📊 Sample Output

* Resume Input: `"Skilled in Python, Machine Learning, and Data Analysis"`
* Predicted Category: **Data Science / AI**

---

## 📈 Future Improvements

* Deploy as a web app using **Flask** or **Streamlit**
* Support **PDF/DOCX** file input for resume parsing
* Use **BERT** or other transformer-based models for better accuracy
* Create a **REST API** for integration into HR software

---

## 👨‍💻 Author

**Vijay Makkad**
[LinkedIn](https://www.linkedin.com/in/vijay-makkad-1573681b3/) • [Email](mailto:vijaymakkad0104@gmail.com)

---

## 📄 License

This project is licensed under the MIT License.

---

