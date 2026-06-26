<div align="center">
  <img src="https://img.icons8.com/color/94/artificial-intelligence.png" alt="Generative AI Guidelines Analysis" width="100" height="100" />
  <h1>Analyzing University Guidelines on Generative AI</h1>
  <p><b>An NLP and Text Mining analysis investigating how academic institutions globally address, regulate, and integrate Generative AI tools in their policies.</b></p>

  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
    <img src="https://img.shields.io/badge/NLTK-154F30?style=for-the-badge&logo=python&logoColor=white" alt="NLTK" />
    <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-Learn" />
  </p>
</div>

---

## 📌 Project Overview

As Generative AI tools like ChatGPT, Claude, and Gemini reshape education, universities worldwide are rushing to establish guidelines. This project applies advanced **Text Mining and Natural Language Processing (NLP)** techniques to analyze, cluster, and extract insights from official university guidelines. 

By analyzing policies across diverse institutions, this project sheds light on institutional stances—ranging from strict prohibition to proactive, ethics-driven integration—while highlighting common concerns regarding academic integrity, data privacy, and intellectual property.

---

## 🧠 Key Features & Methodologies

- **Text Preprocessing & Tokenization**: Comprehensive cleaning, stopword removal, lemmatization, and tokenization using `NLTK` and `Regex`.
- **Sentiment Analysis**: Evaluating the tone and stance (positive/promotional vs. cautious/restrictive) of institutional guidelines.
- **Topic Modeling (LDA)**: Uncovering latent themes and core areas of focus across different university policies.
- **Unsupervised Clustering (K-Means)**: Categorizing universities into distinct cohorts based on their policy similarities and strategic stances toward AI.
- **Visualization**: Rich visual representations including Word Clouds, TF-IDF frequency plots, and cluster distribution charts.

---

## 📁 Repository Structure

```directory
.
├── Text_Mining_Final2_(1)_(1) (1).ipynb                    # Main NLP / Text Mining analysis notebook
├── tm copy final.csv                                       # Constructed dataset containing policy texts
├── Project Report Text Mining.docx                         # Comprehensive academic research report
├── Text Mining Final PPT (1).pptx                          # Presentation slides summarizing findings
└── README.md                                               # Premium documentation
```

---

## 🛠️ Installation & Setup

### Prerequisites
Ensure you have Python 3.8+ and pip installed.

### 1. Clone the Repository
```bash
git clone https://github.com/riteshv7/Analyzing-University-Guidelines-on-generative-AI.git
cd Analyzing-University-Guidelines-on-generative-AI
```

### 2. Install Dependencies
Install the required Python libraries:
```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn wordcloud notebook
```

### 3. Download NLTK Resources
Open Python in your terminal and download the required corpora:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('vader_lexicon')
```

### 4. Run the Analysis
Launch Jupyter Notebook to explore the code:
```bash
jupyter notebook
```
Open and execute `Text_Mining_Final2_(1)_(1) (1).ipynb` (or run it via VS Code/JupyterLab).

---

## 📈 Summary of Findings

1. **Policy Polarization**: Academic policies are largely split between *cautious restrictiveness* (focusing heavily on plagiarism and detection) and *constructive integration* (providing guidelines on how to cite and co-create with AI).
2. **Core Concerns**: Plagiarism, equity of access, data security (feeding intellectual property into public models), and the reliability of AI outputs are the most frequently recurring themes.
3. **Sectoral Trends**: Tech-focused and research-heavy universities show significantly higher positive sentiment scores regarding AI, focusing on literacy rather than prohibition.
