Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Prerequisites

1.You should have Anaconda 2019.03 installed on your local computer.
2.The files that are required for the program to run:
-train_data
-train_label
-test_data

All of these files should be stored in the same folder.

3.The programming language used for this program is Python 3.6.
4.Use Jupyter notebook to run the file.



To run this program on your local machine you need to install the following library/packages on your local computer. 

Textblob
nltk
Wordcloud
Cufflinks 
Plotly

To install these library locally you need to write the following commands in the anaconda prompt:

pip install textblob
pip install wordcloud
pip install plotly
tls.embed('https://plot.ly/~cufflinks/8')
pip install cufflinks --upgrade
nltk.download('vader_lexicon')
nltk.download('wordnet')

#If it gives error even after installing the required nltk library.
nltk.download('all')




