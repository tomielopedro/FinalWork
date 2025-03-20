# Exploring Machine Learning and NLP Solutions for Mental Health 🧠

Today, we want to share a project that marked our journey in data science and highlighted the positive impact that the union of technology and purpose can create.

In the final project for the Data Science Introduction course, my partners Ighor Tatsch Telles, Frederico Franke and I developed a solution that combines Machine Learning (ML) and Natural Language Processing (NLP) to predict depression symptoms based on Reddit posts. Using data from subreddits like Depression, SuicideWatch, and Happy, our goal was to identify patterns associated with emotional states and provide valuable insights.

What We Did? 🔍 Data Exploration: We conducted a thorough analysis of the titles, descriptions, and interactions of the posts, looking for textual signals related to mental health. We used NLP techniques to explore how words, phrases, and user behaviors can reflect emotional states.

## 🛠️ Text Processing, NLP, and Modeling:

Preprocessing: We removed stopwords, applied lemmatization and stemming, using libraries like NLTK and SpaCy, to standardize the data and reduce noise.

Vectorization: The textual data was converted into numerical representations using Count Vectorizer and TF-IDF Vectorizer. Here, NLP plays a key role, as these techniques help capture the importance of words in context, allowing the model to understand the frequency and relevance of terms related to mental health.

Modeling: We then trained various machine learning algorithms, such as Logistic Regression, Random Forest, Naive Bayes, Passive Aggressive Classifier, and SVM, fine-tuning the hyperparameters to optimize performance. While machine learning models were crucial for prediction, NLP techniques allowed us to extract meaningful insights from the textual data, improving model accuracy.

## Key Results 📊 Model Accuracy: After combining different preprocessing techniques, vectorizers, and models, we achieved our best result:

### TF-IDF + SVM with lemmatization: 94.02% accuracy.

This performance reaffirms the powerful combination of NLP and machine learning algorithms. By extracting relevant features from the text using NLP and applying advanced machine learning techniques, we were able to achieve highly accurate predictions.

## Expected Impact
More than just a technical exercise, this project demonstrated how data science can positively impact sensitive areas like mental health. It highlighted how NLP and Machine Learning can be combined to tackle real-world challenges, creating solutions that offer valuable insights and help address complex issues.

We are motivated to continue exploring the potential of Machine Learning and NLP to address challenges and develop solutions that can make a meaningful impact.
