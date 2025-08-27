# Final-Project
# BBC News Classification using Machine Learning

## Project Overview
This project focuses on classifying BBC news articles into five categories — **Business, Entertainment, Politics, Sport, and Tech using Machine Learning and Natural Language Processing (NLP).  
The aim is to build an automated system that can accurately classify news content, reducing manual effort and improving efficiency.

## Repository Contents
- **Final Coding.ipynb** – Jupyter Notebook containing the full code (data preprocessing, feature extraction, model training, evaluation).  
- **Final Project Presentation.pptx** – Presentation slides summarising the project.  
- **Final report.docx** – Detailed project report covering methodology, results, and analysis.
- **Final report.pdf** – Detailed project report covering methodology, results, and analysis.  
- **bbc.zip** – BBC News dataset (compressed).  
- **nltk_data.zip** – NLTK stopwords and WordNet data for preprocessing.  

## Methodology
1. **Preprocessing Pipeline**  
   - Lowercasing, punctuation/digit removal  
   - Stopword removal using NLTK  
   - Tokenization  
   - Lemmatization  

2. **Feature Extraction**  
   - TF-IDF vectorization with top 5,000 features  

3. **Models Trained**  
   - Logistic Regression  
   - Support Vector Machine (SVM – LinearSVC)  
   - Multinomial Naive Bayes  
   - Random Forest  

4. **Model Optimization**  
   - Hyperparameter tuning with GridSearchCV (Logistic Regression)  

5. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix  

## Results
- **Logistic Regression** achieved the best accuracy with **98%**, followed by SVM (~97.7%).  
- Naive Bayes (~95%) and Random Forest (~96.5%) also performed well.  
- Logistic Regression was the most efficient and scalable model for this dataset.  

## Insights
- Dataset was balanced, avoiding bias.  
- TF-IDF features captured topic-specific words (e.g., *football* → Sport, *market* → Business).  
- Preprocessing played a key role in improving performance.  

## Future Work
- Apply Deep Learning models like LSTM or BERT.  
- Use larger, real-time news datasets.  
- Deploy as a web app for practical use.  
