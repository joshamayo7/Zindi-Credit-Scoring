# Zindi-Credit-Scoring

I recently competed in my first Machine Learning competition on Zindi 🚀, where the challenge was to build a classification model to predict customer loan defaults. The scoring metric, the F1 score, emphasized the importance of balancing precision and recall. This competition was an excellent opportunity to apply and refine my machine learning workflow, using Python packages for feature engineering and ensembling models for robust model validation.

One of the unique challenges in this competition was the dataset split: the training data consisted of Kenyan customers, while the test set included Ghanaian customers. Additionally, the dataset had a significant class imbalance (Very few loan defaulters), which further complicated model training and evaluation. These challenges required the model to not only handle differences in data distributions (New country) but also maintain robustness in predicting minority classes.

Performance Overview
Local Cross-Validation: Achieved a mean F1 score of 0.86, with the highest fold reaching 0.9, demonstrating strong performance during development.
Public Leaderboard: Ended with a score of 0.69 (Rank 275/1,024) on 30% of the test data.
Private Leaderboard: Scored 0.64 on the full test set, revealing challenges in generalization to unseen distributions.
Interesting Insight: One submission scored 0.66 on the private leaderboard but I did not select it due to its lower public score. Even a 0.02 difference can significantly impact competition rankings.

Competition Takeaways
Feature Engineering: Crafting new features had a far greater impact on performance than fine-tuning parameters. This underscored the importance of designing features that capture meaningful relationships in the data.
Generalization: Addressing domain shifts, like those between Kenyan and Ghanaian data, is essential for building models that are reliable.
Trusting Cross-Validation: Relying solely on public leaderboard scores can be misleading. Trusting local validation results ensures more robust model evaluation.

This competition was not only a rewarding technical experience but also a valuable reminder of the challenges of developing machine learning models in real-world scenarios. I look forward to participating in more competitions this year to continue refining my skills and tackling impactful challenges in sports analytics, healthcare, and financial modeling.
