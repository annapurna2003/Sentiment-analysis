# Sentiment-analysis

NLP is the analysis of words and not sentences

<h2>A few questions you might have while reading the code</h2>

<h4>Why are we using utf-8 while reading the file?</h4>
utf-8 is used in reading files as while we copy text from any site or blog, the text copied could be encoded, using utf-8 while reading the text file helps read the proper file without encoded value. ( basically, decrypts and the encrypted file so we can read the plain text)

<h4>Why should we change all the letters or characters in the text file to lowercase?</h4>
Movie != movie [Case sensivity] 
So we converted all the cases to lowercase to have better insight into the sentiments in it

<h4>What does tokenization mean?</h4>
Tokenization - breaking the sentence into words. saves each word in a list

<h4>What are stop words?</h4>
Stop words are the words that add no meaning to the sentence and hence can be ignored from the list while we make tokenization of the file
