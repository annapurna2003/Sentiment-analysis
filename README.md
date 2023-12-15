# Sentiment-analysis

NLP is analysis of words and not sentance

Few questions you might have while reading the code

Why are we using utf-8 while reading the file?
utf-8 is used in reading file as while we copy text from any site or blog, the text copied could be encoded, by using utf-8 while reading the text file helps in reading the proper file without encoded value. ( basically decrypts and the encrypted file so we can read the plain text)

Why should we change all the letters or charecters in the text file to lower case?
Movie != movie [Case sensivity]
So we convert all the cases to lower case to have better insight about the sentiments in it

What does tokenization mean?
Tokenization - breaking the sentence into words. saves each word in a list

What are stop words?
Stop words are the words which add no meaning to the sentance hence can be ignored from the list while we make tokenication of the file
