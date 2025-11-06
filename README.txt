Theme Park Review Analysis Ð Text Preprocessing and Topic Modeling
Overview:
This project analyses customer review data from the ThemeParkReviews.csv file. It applies Natural Language Processing (NLP) techniques to clean raw text, and uses Topic Modeling (LDA) to extract common themes present in customer feedback. The goal is to demonstrate practical text analytics skills that can be applied in real business scenarios.

1. Objectives
* Clean and structure customer review text.
* Create a Bag-of-Words representation for modeling.
* Build a Topic Modeling pipeline using GensimÕs LDA.
* Extract and display dominant topics and keywords.

2. Dataset
* File used: ThemeParkReviews.csv
* Key column involved: Review_Text
* Contains customer-written reviews about theme park experiences.

3. Process Workflow
1. Import dataset
2. Text preprocessing steps:
o Convert to lowercase
o Tokenize text
o Remove punctuation
o Remove stopwords using NLTK
o Apply stemming (PorterStemmer)
3. Create dictionary (id2word) and corpus using Gensim
4. Build LDA (Latent Dirichlet Allocation) model
5. Output:
o New column: Cleaned_Review_Text
o List of topics with top keywords

4. Tools and Libraries Used
* Python
* pandas
* numpy
* nltk
* gensim

6. How to Run This Project
# Create virtual environment (optional)
python -m venv env
source env/bin/activate      # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the analysis script
python src/preprocessing_and_lda.py

7. Future Improvements
* Add topic visualization using pyLDAvis or word clouds
* Perform sentiment analysis
* Build dashboard with Tableau or Power BI
* Deploy as a simple web app (Flask/Streamlit)

8. Author
Piyush Sharma
LinkedIn: www.linkedin.com/in/piyushsharmaaa
