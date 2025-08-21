The extensive propagation of false news on digital platforms poses a serious challenge to public opinion, highlighting the importance of robust automated detection systems.
This work presents a methodical approach to identifying false news using machine learning techniques, focusing on text preparation, sentiment analysis, and classification. 
We use a mixed dataset of labeled false and authentic news stories, with rigorous data cleaning and feature extraction algorithms. 
To determine the emotional tone of the articles, sentiment analysis is conducted using the VADER model. 
For classification, we use the Light Gradient Boosting Machine (LightGBM) model, which is further tuned using Optuna to achieve peak performance. 
Our data demonstrate the model's performance, with a 99.98% accuracy and a log loss of 5.311e-5. 
Additionally, we examine the sentiment distribution across different news topics, uncovering patterns that enhance the detection process. This research contributes to developing an automated fake news detection system, offering a robust model adaptable to various datasets and contexts.
