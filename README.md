# 🍽️ Sentiment Analysis of Restaurant Reviews

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

> A comprehensive machine learning project for analyzing customer sentiments in restaurant reviews using Natural Language Processing (NLP) techniques.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🔍 Overview

Sentiment analysis, also known as opinion mining, is a powerful Natural Language Processing (NLP) technique used to determine and evaluate the sentiments and opinions expressed in textual data. This project applies machine learning algorithms to classify restaurant reviews as positive or negative, helping businesses understand customer satisfaction and make data-driven decisions.

## ✨ Features

- **Text Preprocessing**: Comprehensive data cleaning including punctuation removal, tokenization, stopword removal, and lemmatization
- **Machine Learning Classification**: Implementation of supervised learning algorithms for sentiment prediction
- **Data Visualization**: Clear visual representations of sentiment distributions and trends
- **Reproducible Analysis**: Well-documented Jupyter notebook with step-by-step implementation
- **Real-world Dataset**: Analysis of actual restaurant customer feedback

## 📊 Dataset

The dataset (`Restaurant_Reviews.tsv`) contains 1,000 restaurant reviews with the following structure:

- **Review**: Text of the customer review
- **Liked**: Binary label (1 = Positive, 0 = Negative)

The dataset was collected from restaurant feedback surveys and includes diverse customer opinions about food quality, service, ambiance, and overall experience.

## 🚀 Installation

### Prerequisites

- Python 3.7 or higher
- pip package manager
- Jupyter Notebook

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/OMAR622-ai/-Sentiment-Analysis-of-Restaurant-Reviews-.git
   cd -Sentiment-Analysis-of-Restaurant-Reviews-
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Download NLTK data** (if needed)
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('wordnet')
   ```

## 💻 Usage

1. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Open the analysis notebook**
   - Navigate to `Sentiment_Analysis.ipynb`
   - Run cells sequentially to reproduce the analysis

3. **Explore the data**
   - Load and examine the restaurant reviews dataset
   - Visualize sentiment distributions
   - Train and evaluate the sentiment classification model

## 🔬 Methodology

### 1. Data Collection
The dataset was obtained from a restaurant feedback survey conducted over a specific period, collecting comments and ratings from customers who had recently dined at various restaurants.

### 2. Data Preprocessing
The textual data undergoes several preprocessing steps:

- **Text Cleaning**: Removing punctuation, special characters, and irrelevant symbols
- **Tokenization**: Splitting sentences into individual words or tokens
- **Stopword Removal**: Eliminating common and uninformative words (e.g., "the," "and," "in")
- **Lemmatization**: Reducing words to their base or dictionary form to standardize text

### 3. Sentiment Analysis
Sentiment analysis is performed using supervised machine learning approaches:

- **Feature Extraction**: Converting text data into numerical features using techniques like Bag of Words or TF-IDF
- **Model Training**: Training classifiers on labeled data (positive/negative) to predict sentiment
- **Model Evaluation**: Assessing performance using metrics like accuracy, precision, recall, and F1-score

## 📈 Results

The sentiment analysis yielded valuable insights:

### Overall Sentiment Distribution
- **Positive Reviews**: Analysis shows the percentage of satisfied customers
- **Negative Reviews**: Identifies areas needing improvement

### Key Findings

**Common Positive Sentiments:**
- Praise for food quality and taste
- Compliments for attentive and friendly staff
- Positive remarks about restaurant ambiance

**Common Negative Sentiments:**
- Complaints about long wait times for service
- Criticisms of portion sizes or pricing
- Dissatisfaction with cleanliness or hygiene

### Business Impact
The analysis provides actionable insights for:
- Enhancing customer satisfaction
- Improving service quality
- Making data-driven operational decisions
- Identifying strengths and areas for improvement

## 📁 Project Structure

```
-Sentiment-Analysis-of-Restaurant-Reviews-/
│
├── Sentiment_Analysis.ipynb    # Main analysis notebook
├── Restaurant_Reviews.tsv      # Dataset file
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
├── LICENSE                     # MIT License
└── .gitignore                 # Git ignore file
```

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms
- **NLTK**: Natural language processing
- **Jupyter Notebook**: Interactive development environment

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Dataset source and inspiration for sentiment analysis in the restaurant industry
- The open-source community for providing excellent NLP tools and libraries
- Contributors and maintainers of scikit-learn, NLTK, and other dependencies

## 📧 Contact

For questions, suggestions, or collaboration opportunities, please open an issue on GitHub.

---

**Made with ❤️ for better understanding of customer sentiments**
