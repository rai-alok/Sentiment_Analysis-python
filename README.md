# Sentiment_Analysis-python

 Project Overview

This project focuses on sentiment analysis and rating prediction using Amazon product reviews.
The objective is to analyze customer review text and predict the corresponding star rating using Natural Language Processing (NLP) and supervised machine learning techniques.

⸻

📂 Dataset
	•	Amazon product reviews dataset
	•	Data includes review text and star ratings (1–5)
	•	Dataset was cleaned and preprocessed before modeling

⸻

🛠 Tools & Technologies Used
	•	Python
	•	Pandas, NumPy
	•	NLP preprocessing (tokenization, stopword removal)
	•	TF-IDF for feature extraction
	•	TextBlob for sentiment polarity
	•	Scikit-learn (Logistic Regression)

⸻

🔄 Methodology
	•	Cleaned and preprocessed raw review text
	•	Converted text data into numerical features using TF-IDF
	•	Applied sentiment scoring to analyze polarity
	•	Built a Logistic Regression model to predict star ratings
	•	Evaluated model performance using accuracy and classification metrics

⸻

📊 Results
	•	Achieved ~72% accuracy in predicting review ratings
	•	Strong correlation observed between sentiment polarity and star ratings
	•	Model performed best for extreme ratings (very low and very high)

⸻

🔍 Key Insights
	•	Positive sentiment strongly aligns with higher ratings
	•	Negative sentiment is a strong indicator of low ratings
	•	Frequently occurring words provide actionable business insights
