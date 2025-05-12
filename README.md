Applied AI - NLP Text Classification with AG News
This repository contains an Applied AI project focused on text classification using the AG News dataset. The goal of the project is to compare multiple machine learning models (both traditional and deep learning-based) for classifying news articles into one of four categories: World, Sports, Business, and Science/Technology.

Project Overview
The project explores the following:

Traditional Machine Learning Models: Such as Naive Bayes, SVM, Logistic Regression, Random Forest, and k-NN.

Deep Learning Models: Including RNN, LSTM, GRU, and Transformer-based models.

The AG News dataset was preprocessed and used for training and evaluation. Key steps include tokenization, vectorization using TF-IDF and Word2Vec, and hyperparameter tuning for deep learning models.

Models and Evaluation
Traditional Models: Evaluated on accuracy, precision, recall, and F1 score.

Deep Learning Models: RNN, LSTM, GRU, and Transformer models were trained and compared to assess performance on text classification tasks.

Project Structure

/project-directory

    ├── notebooks/            # Jupyter Notebooks with model implementations
    
    ├── data/                 # Datasets (if any)
    
    ├── models/               # Trained models and configurations
    
    ├── report/               # (Optional) Project report (not included in GitHub)
    
    ├── README.md             # Project documentation


Key Libraries:

scikit-learn
tensorflow / keras
pandas
numpy
matplotlib / seaborn


Additional Notes:
The project includes Jupyter Notebooks for implementing machine learning and deep learning models.

You can also find visualizations, model evaluation results, and insights in the notebook files.
