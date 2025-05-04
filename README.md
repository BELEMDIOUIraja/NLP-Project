# Kano Model ML Classifier

## 📌 Project Description
This project is a **Machine Learning-based classification system** for customer feedback using the **Kano Model**. It analyzes user reviews and categorizes them into different Kano categories to help businesses understand customer satisfaction levels. 

The project integrates **Natural Language Processing (NLP)** and **Large Language Models (LLM)**, including **Google Gemini via OpenRouter API**, to classify feedback efficiently.

## 🚀 Features
- **Text Classification**: Uses NLP techniques to classify customer feedback.
- **Kano Model Analysis**: Categorizes customer requirements into different Kano categories.
- **Interactive Visualization**: Generates graphical insights from the data.
- **Machine Learning Pipeline**: Preprocessing, model training, and evaluation.

## 🛠️ Technologies Used
- **Python**
- **scikit-learn** for Machine Learning
- **NLTK** for NLP processing
- **Matplotlib & Seaborn** for visualization
- **OpenRouter API** for LLM-based text classification
- **Jupyter Notebook** for development and testing

## 📥 Installation
```bash
git clone https://github.com/yourusername/Kano-Model-ML.git
cd Kano-Model-ML
pip install -r requirements.txt
```

## 📌 Usage
1. Prepare your dataset (customer feedback in text format).
2. Run the classification script:
   ```bash
   python classify_reviews.py
   ```
3. View the Kano Model graph in the output directory.

## 📂 Project Structure
```
Kano-Model-ML/
│-- data/                  # Sample dataset
│-- notebooks/             # Jupyter notebooks
│-- src/                   # Source code
│   │-- preprocess.py      # Data preprocessing
│   │-- classify_reviews.py # Model training & prediction
│-- requirements.txt       # Required Python packages
│-- README.md              # Project documentation
```


