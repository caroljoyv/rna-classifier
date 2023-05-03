# RNA Sequence Classification using Machine Learning
This project aims to classify RNA sequences based on various features, including Fickett score, CpG islands, ORF length, ORF ratio, transcript length, GC content, and AT dinucleotide composition. We use four machine learning models - logistic regression, naive Bayes, random forest, and support vector machine (SVM) - to classify the RNA sequences.

## Dataset
The dataset used in this project consists of RNA sequences and their corresponding labels. Each RNA sequence is represented as a string of characters, and each label indicates whether the sequence belongs to a certain class or not.

## Features
We extract the following features from the RNA sequences:

Fickett score
CpG islands
ORF length
ORF ratio
Transcript length
GC content
AT dinucleotide composition

## Models

We use the following machine learning models to classify the RNA sequences:

Logistic regression
Naive Bayes
Random forest
Support vector machine (SVM)
We train each model on the extracted features and evaluate their performance using various metrics, such as accuracy, precision, recall, and F1 score.

## Usage
To run the project, follow these steps:

Clone the repository: git clone https://github.com/<username>/<repository-name>.git
Install the required packages: pip install -r requirements.txt
Run the Jupyter Notebook: jupyter notebook
Open the RNA Sequence Classification.ipynb notebook and run the cells.
Results
We achieve the following results on the test set:

## License
This project is licensed under the MIT License.

## Conclusion
This project demonstrates how machine learning can be used to classify RNA sequences based on various features. We use four machine learning models - logistic regression, naive Bayes, random forest, and support vector machine - to classify the RNA sequences and achieve high accuracy and F1 scores. The insights gained from this project can be used to improve the understanding and analysis of RNA sequences in bioinformatics research.
