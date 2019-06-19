# Classification using Naive Bayes


In the mini-project, you'll learn the basics of text analysis using a subset of movie reviews from the rotten tomatoes database. You'll also use a fundamental technique in Bayesian inference, called Naive Bayes. This mini-project is based on Lab 10 of Harvard's CS109 class. Please free to go to the original lab for additional exercises and solutions.

We do feature extraction using Vectorizer methods of sklearn, train and testing model and compute performance metrics as F1 score, Recall, Precition, ROC curves. We apply cross-validation, and iteration over the hyper-parameteres of every model used, to maximize the likelihood in the case of Naive Bayes and F1 score in Random Forest. 

Additionaly, we apply some techniques to normalized the corpus of reviews used, as the following: lemmatization, delete stop-words, delete special characters and tokenization using one of the most popular libraries in Natural Language Processing: nltk.

## Getting Started

### Prerequisites

- This notebook loads `./critics.csv` locates in the same folder.
- [Download Anaconda](https://www.anaconda.com/distribution/).
- Run Anaconda Navigator and launch a jupyter notebook and open the file `Mini_Project_Naive_Bayes.ipynb`
- Install request package from Terminal.

Other libraries applied in this project (numpy, scipy, matplotlib, pandas, seaborn, sklearn, six.moves) do not require installation (default packages in anaconda). They only need to be imported in the notebook.

### Installing

```bash
pip install --user -U nltk
```
