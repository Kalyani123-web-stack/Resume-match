# Resume-match(ML+NLP)
A machine learning-based system that matches resumes to job descriptions using natural language processing and evaluates the matching accuracy. Built using Python, scikit-learn, and NLP libraries, this tool helps recruiters identify the most suitable candidates based on content relevance and semantic similarity.
Key features:
1.Resume Parsing: Extracts skills, experience, education, and keywords from resume text (PDF or text format).

2.Job Description Analysis: Processes job descriptions to extract required skills and responsibilities.

3.Text Preprocessing: Includes tokenization, stopword removal, lemmatization, and TF-IDF vectorization.

4.Semantic Matching: Uses vector similarity (e.g., cosine similarity) to calculate how closely resumes match job descriptions.

5.Machine Learning Scoring: Optionally uses supervised ML models (e.g., LogisticRegression, RandomForest) to classify or score matches.

6.Accuracy Evaluation: Calculates accuracy, precision, recall, F1-score using labeled data to assess model performance.
