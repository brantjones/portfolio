# portfolio

A portfolio of data science projects (in progress)...

* [NLP Recommendations](dc/deep_recommendations.ipynb)
  * extracts features using a 5000-dimensional TF-IDF model with bi-grams and tri-grams
  * includes qualitative visualization of feature vectors using TSNE
  * replaces the usual cosine similarity recommendation ranking with a neural network trained on individuals' prior interactions
  * custom quantitative model validation using recall@10 applied to carefully split training and test data
  * written in python (with numpy, pandas, pyplot, sklearn) using TfidfVectorizer and keras TensorFlow
  
  * (cf. [prior version](dc/dc%20recommendations.ipynb))
