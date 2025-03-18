#  Fake News Prediction Using Machine Learning  

##  Overview  
This project addresses the increasing challenge of **fake news detection** by implementing **machine learning techniques** to classify news articles as real or fake.  
A variety of **supervised learning models** are evaluated, with a focus on **enhancing prediction accuracy** through **advanced text preprocessing, TF-IDF vectorization, and feature engineering**.  

Logistic Regression serves as a baseline model, and its performance is systematically compared with **ensemble methods** to determine the most effective approach for **fake news classification**.  

---

##  Objectives  
- ✅ Develop a **machine learning-based classification system** for fake news detection.  
- ✅ Implement **TF-IDF vectorization** and **feature engineering** to enhance text representation.  
- ✅ Conduct a **comparative analysis** of multiple machine learning models.  
- ✅ Optimize **Logistic Regression performance** and benchmark it against **ensemble learning models**.  

---

##  Dataset & Preprocessing  
- **Dataset**: 20,800 labeled news articles ([Kaggle Source](https://www.kaggle.com/)).  
- **Preprocessing Steps**:  
  -  **Text Cleaning** → Removal of HTML tags, special characters, and stopwords.  
  -  **Feature Engineering** → Merging `author` and `title` into a new `content` feature.  
  -  **Vectorization** → Applying **TF-IDF (Term Frequency-Inverse Document Frequency)** for text transformation.  

---

##  Machine Learning Models Evaluated  
| Model | Initial Accuracy | Improved Accuracy |  
|----------------|----------------|----------------|  
| **Logistic Regression** (Baseline) | **49%** | **98%** (After refined preprocessing) |  
| Random Forest | - | 91% |  
| SVM | - | 89% |  
| KNeighbors | - | 85% |  
| Decision Tree | - | 86% |  
| AdaBoost | - | 90% |  
| Bagging | - | 92% |  
| **Gradient Boosting** | - | **99%** |  
| **XGBoost** (Best) | - | **99.2%** |  

 **Key Finding:** **XGBoost and Gradient Boosting** demonstrated the highest classification accuracy (**99%+**), outperforming other models in detecting fake news.  

---

##  Key Features  
- ✅ **Fake News Classification** → Machine learning algorithms predict whether news is real or fake.  
- ✅ **Advanced Data Preprocessing** → Techniques such as **TF-IDF vectorization** and feature engineering enhance accuracy.  
- ✅ **Model Benchmarking** → A comparative analysis of various machine learning models is conducted.  
- ✅ **High Accuracy Prediction** → Ensemble models achieve **up to 99.5% accuracy**.  

---

##  Technologies Used  
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Machine Learning Models** (Logistic Regression, XGBoost, Random Forest, etc.)  
- **NLP Techniques** (TF-IDF, Feature Engineering, Text Cleaning)  
- **Jupyter Notebook** for model development and evaluation  

---

##  Future Scope  
-  **Integrating Deep Learning Models** → Implementing **LSTMs and Transformers** for enhanced text classification.  
-  **Multimodal Analysis** → Combining **text, images, and social engagement data** for improved fake news detection.  
-  **Deployment** → Developing a web-based tool to make real-time predictions accessible to users.  

---

##  Contribution  
Contributions to further improve the project are welcome. For modifications, fork the repository and submit a pull request.  

 **Advancing AI-driven fake news detection through machine learning.**   

