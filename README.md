# portfolio

A portfolio of data science projects (in progress)...

* [NLP Recommendations](dc/deep_recommendations.ipynb)
  * extracts features from natural language text using a 5000-dimensional TF-IDF model with bi-grams and tri-grams
  * includes qualitative visualization of feature vectors using sklearn.manifold.TSNE
  * replaces the usual cosine similarity recommendation ranking with a neural network trained on individuals' prior interactions
  * custom quantitative model validation using recall@10 applied to split training and test data
  * written in python (with numpy, pandas, pyplot, sklearn, scipy.sparse, keras) using TfidfVectorizer and keras Sequential model (TensorFlow implementation)
  * (cf. [prior version](dc/dc%20recommendations.ipynb))

* [Supervised Learning](student/analysis.ipynb)
  * features cross-validation with upsampling to handle an imbalanced dataset and a custom score function for model selection.
  * written in python (with numpy, pandas, pyplot, sklearn) using LogisticRegression, RandomForestClassifier, DecisionTreeClassifier
