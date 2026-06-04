# Restaurant-Review-Sentiment-Analysis
A Natural Language Processing project that classifies restaurant reviews as positive or negative using a TF-IDF and logistic regression pipeline.

Model selection uses cross-validated grid search over vocabulary size, n-gram range, and regularization strength, with a stratified held-out test set for unbiased evaluation.

The final model achieves 80% test accuracy and is applied to an unlabelled batch of fresh reviews.
