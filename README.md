# student-feedback
NLP based web application that analyses the sentiment behind student feedbacks using Naive Bayes Classifier.


pip install virtualenv 
virtualenv env
env\Scripts\activate 
pip install -r requirements.txt 
flask db migrate   
flask add-admin
python -m textblob.download_corpora
flask run