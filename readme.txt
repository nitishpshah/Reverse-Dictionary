Requirments before running the code

1. Download the pre-trained Google Word2Vec model by going on the link - https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit
2. Extract and copy-paste it in the same folder as the source-code.
3. Install all the necessary python packages - gensim, pyemd.

How to execute

1. Run the revDict.py file using python 2.
2. Wait for a few seconds for the program to load the dictionary and the Word2Vec model.
3. When promted for an input phrase, enter the sentence whose symantically equivalent word you want to find.
4. When promted for first letter of the expected result, enter the first alphabet of word you are expecting as the output (This is done to restrict the size of the dictionary, in order to boost the search speed).
5. Wait for the search to complete, the result will be printed in the form of a list (of length 20 - which can be adjusted), and this list will be in desecnding order of similarity.