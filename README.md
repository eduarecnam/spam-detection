# SPAM-Detection through Machine Learning Techniques

This project is focused on the study of Machine Learning techniques for spam detection. The techniques used on this project are:
- Naive Bayes
- KNN
- SVM 
- Logistic Regression 
- Decision Tree 
- Random Forest

# Clarifications

- *This project it's been structured so that every folder is a different dataset, the treatment and strategies followed are the same for every dataset though.*
- *Due to its good documentation and extended use, the scikit-learn library implementation, it's been chosen one for carrying out all of the models creation.*

# Datasets

These techniques have been tested against the dataset whose description you can see next:

- **Enron spam dataset (enron on the repository):** This dataset was used on the paper titled *Spam Filtering with Naive Bayes - Which Naive Bayes?* proceeded from the third conference about email and anti-spam in 2006. There are two versions of this dataset. A pre-processed version (the one used on this project) and a raw version. On the pre-processed version there aren't duplicate messages, plus, a random sub-sample has been done, in order to get the ratios of spam emails and legit emails. This dataset can be downloaded from: http://www2.aueb.gr/users/ion/data/enron-spam/

- **PU CORPORA dataset:** This dataset has been used to develop the paper titled *Filter Unsolicited Commercial E-mail* by *I. Androutsopoulos, G. Paliouras, E. Michelakis.* This dataset counts with 4 sub-directories which content 11 subdirectories (1 per fold used on cross-validation process), plus one directory called *unused*, which content discard emails, to store the same number of legit emails and spam emails. This dataset can be downloaded from: http://www.aueb.gr/users/ion/data/PU123ACorpora.tar.gz

- **spam_ham_dataset:** This dataset is a subset of Enron's dataset. It's a .CSV file which has 4 columns to make easier the use of this dataset. This file has been created by *Venkatesh Garnepudi*. This file can be downloaded from: https://www.kaggle.com/venky73/spam-mails-dataset/download

- **Spamassasin dataset:** This dataset it's been divided into spam/legit email of easy and hard detection. It contains 6047 emails, with 31% of spam emails, all of the emails keep their headers and some of the addresses have been offuscated, some of the hostnames have been replaced by the string spamassasin.taint.org. This dataset can be downloaded from https://spamassassin.apache.org/old/publiccorpus/

- **Spambase dataset:** Created by *Mark Hopkins, Erik Reeber, George Forma, Jaap Suermondt at Hewlett-Packard Labs, 1501 Page Mill Rd. Palo Alto, CA 94304*. The emails you'll find on this dataset come from the email admininistrator and from people who'd sent non-legit emails. By other hand, legit emails come from personal emails and working emails. This dataset can be downloaded from: https://archive.ics.uci.edu/ml/datasets/spambase

# Biblioraphy

On this section you'll find all of the resources which have made possible this project. That's why I'd like to leverage this section to thank all them

- *email spam detection:* https://www.youtube.com/watch?v=cNLPt02RwF0
- *Missing values strategies:* https://www.kaggle.com/code/alexisbcook/missing-values/tutorial
- *Naive Bayes classifier explained:* https://towardsdatascience.com/naive-bayes-classifier-explained-50f9723571ed
- *Enron dataset spam classifier:* https://www.kaggle.com/code/vermichel/intro-to-nlp-spam-classifiier/notebook
- *Word stemmer:*  https://www.nltk.org/howto/stem.html
- *Spamassasin dataset - spam classification:* https://sdsawtelle.github.io/blog/output/spam-classification-part1-text-processing.html
- *Word steaming with nltk:* https://www.geeksforgeeks.org/python-stemming-words-with-nltk/
- *What Cross-Validations is?* https://www.kaggle.com/alexisbcook/cross-validation#What-is-cross-validation?
- *Cross-Validation scikit-learn implementation documentation:* https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html
- *Getting the Right Number of Folds on Cross-Validation:* https://datascience.stackexchange.com/questions/28158/how-to-calculate-the-fold-number-k-fold-in-cross-validation
- *When and how to shuffle datasets on Cross-Validation:* https://www.youtube.com/watch?v=Ld8-_WP0G90
- *Understanding a classification report:* https://medium.com/@kohlishivam5522/understanding-a-classification-report-for-your-machine-learning-model-88815e2ce397
- *Confusion matrix interpretation:* https://towardsdatascience.com/understanding-the-confusion-matrix-and-how-to-implement-it-in-python-319202e0fe4d#3378
- *How to get accuracy on a machine learning model:* https://algorithmia.com/blog/the-value-of-model-accuracy
- *KNN method explanation:* https://www.youtube.com/watch?v=HVXime0nQeI
- *How to get the optimal value of K parameter on KNN method:* https://towardsdatascience.com/how-to-find-the-optimal-value-of-k-in-knn-35d936e554eb
- *What's up when K value in increased on KNN method?* https://askdatascience.com/170/what-happens-asthe-k-increases-in-the-knn-algorithm#:~:text=The%20smaller%20values%20for%20k,algorithm%20seems%20a%20reasonable%20choice
- *K parameter value on KNN:* https://stackoverflow.com/questions/11568897/value-of-k-in-k-nearest-neighbor-algorithm
- *How to choose the right value of K parameter on KNN method:* https://www.quora.com/How-can-I-choose-the-best-K-in-KNN-K-nearest-neighbour-classification
- *Getting the ideal value of K parameter on KNN method:* https://machinelearninghd.com/k-nn-k-nearest-neighbors-starter-guide/
- *SVM method main ideas:* https://www.youtube.com/watch?v=efR1C6CvhmE
- *Logistic Regression explained:* https://www.youtube.com/watch?v=yIYKR4sgzI8
- *Odds and Log(Odd) well explained:* https://www.youtube.com/watch?v=ARfXDSkQf1Y
- *Decision Trees and clasification well explained:* https://www.youtube.com/watch?v=_L39rN6gz7Y
- *Decision Trees:* https://www.youtube.com/watch?v=7VeUPuFGJHk
- *Random Forest, use, creation and evaluation:* https://www.youtube.com/watch?v=J4Wdy0Wc_xQ
- *KNN method scikit-learn implementation:* learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
- *Data standarization:* https://www.sisense.com/glossary/data-standardization/
- *Data standarization and normalization:* https://www.analyticsvidhya.com/blog/2020/04/feature-scaling-machine-learning-normalization-standardization/#h2_1
- *Python library for data standarization:* https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html
- *SVM method scikit-learn implementation:* https://scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVC.html#sklearn.svm.LinearSVC
- *Logistic Regression scikit-learn implementation::* https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
- *Decision Trees method scikit-learn implementation:* https://scikit-learn.org/stable/modules/tree.html
- *Random Forest method scikit-learn implementation:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

