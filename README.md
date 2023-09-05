# Text-Classification
Converted the raw documents fetched from the 20newsgroups dataset into a vocabulary frequency table discounting the stop words.
</br>
Created a dictionary and engineered a Multi Naive Bayes function to classify the documents and it achieved an accuracy of 86%.
</br>
Printed the classification report for both inbuilt and self-engineered implementations and approximately got the same accuracy in both of them.
</br>
I have imported the stopwords from nltk and copied more of them from internet.
</br>
Instead of split() function, I am using the tokenizer which makes the job much easier.
</br>
Instead of manually downloading the data from the internet, I have downloaded it using sklearn.datasets.fetch_20newsgroups
