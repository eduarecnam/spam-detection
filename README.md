# SPAM-Detection through Machine Learning Techniques

This project is focused on the study of Machine Learning techniques for spam detection. The techniques used on this project are:
- Naive Bayes
- KNN
- SVM 
- Logistic Regression 
- Decision Tree 
- Random Forest

*Due to its good documentation and extended use, the scikit-learn library implementation, it's been chosen one for carrying out all of the models creation.*


This techniques have been tested against the datasets you can see next:
- **Enron spam dataset (enron on the repository):** This dataset was used on the paper titled *Spam Filtering with Naive Bayes - Which Naive Bayes?* proceeded from the third conference about email and anti-spam in 2006. There are two versions of this dataset. A pre-processed version (the one used on this project) and a raw version. On the pre-processed version there aren't duplicate messages, plus, a random sub-sample has been done, in order to get the ratios of spam emails and legit emails. This dataset can be downloaded from: http://www2.aueb.gr/users/ion/data/enron-spam/

- **PU CORPORA dataset:** This dataset has been used to develop the paper titled *Filter Unsolicited Commercial E-mail* by *I. Androutsopoulos, G. Paliouras, E. Michelakis.* This dataset counts with 4 sub-directories which content 11 subdirectories (1 per fold used on cross-validation process), plus one directory called *unused*, which content discard emails, to store the same number of legit emails and spam emails. This dataset can be downloaded from: http://www.aueb.gr/users/ion/data/PU123ACorpora.tar.gz

- **spam_ham_dataset:** This dataset is a subset of Enron's dataset. It's a .CSV file which has 4 columns to make easier the use of this dataset. This file has been created by *Venkatesh Garnepudi*. This file can be downloaded from: https://www.kaggle.com/venky73/spam-mails-dataset/download

- **Spamassasin dataset:** This dataset it's been divided into spam/legit email of easy and hard detection. It contains 6047 emails, with 31% of spam emails, all of the emails keep their headers and some of the addresses have been offuscated, some of the hostnames have been replaced by the string spamassasin.taint.org. This dataset can be downloaded from https://spamassassin.apache.org/old/publiccorpus/

- **Spambase dataset:** Created by *Mark Hopkins, Erik Reeber, George Forma, Jaap Suermondt at Hewlett-Packard Labs, 1501 Page Mill Rd. Palo Alto, CA 94304*. The emails you'll find on this dataset come from the email admininistrator and from people who'd sent non-legit emails. By other hand, legit emails come from personal emails and working emails. This dataset can be downloaded from: https://archive.ics.uci.edu/ml/datasets/spambase


