# Term-Project---HashTag-Recommendation-System-For-Stack-Overflow-Dump


parse_pickle.py parses the given pickle file and dumps a text file where the data is of the following form

sentence <<<<<tag1,tag2,tag3>>>>>

gensim_word2vec.py takes a file containing only sentences and generates the word2vec model file. We did this on the original stackoverflow datadump

pickle_out.txt and pickle_out2.txt consists of sentences with a total of 10 and 5 tags respectively

hashtag_cnn.py takes a text file and model file as input trains the CNN and provides the accuracy

We have obtained the following results

pickle_out.txt 10 classes Precision: 10% Recall 10%
pickle_out2.txt 5 classes Precision 24% Recall 20%
