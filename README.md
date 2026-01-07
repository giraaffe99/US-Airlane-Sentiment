This project uses Natural Language Processing (NLP) and Machine Learning to analyze customer sentiment from tweets regarding US airlines. The goal is to identify common complaints and build a model that can automatically classify feedback into Positive, Neutral, or Negative categories.

The Tech Stack
Language: Python

Environment: Jupyter Notebook / VS Code

Libraries: Pandas (Data manipulation), Matplotlib/Seaborn (Visualization), Scikit-Learn (Machine Learning), NLTK (Text cleaning)

Top Complaint: Based on the analysis, the #1 reason for negative sentiment across all US airlines was "Late Flight".

Airline Performance: Visualizations revealed that specific airlines (like United or US Airways) received a much higher volume of negative tweets compared to others during the study period.

Temporal Trends: Sentiment analysis over time showed significant spikes in negative feedback on specific days, likely corresponding to industry-wide delays or weather events.

 Results
I compared three different models to find the most accurate predictor of sentiment:

Logistic Regression: Achieved the highest accuracy and was the most efficient.

Naive Bayes: Performed well for a baseline model due to its speed with text data.

Random Forest: Provided robust results but required more computational power.
