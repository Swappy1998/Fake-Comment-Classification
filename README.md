# Fake-Comment-Classification
My project is fake comment classification in which i am classifying into two classes using Natural Language Techniques. The dataset is used in this project is publicly available on hackerrank . This dataset contains the author name , comment and class of comment (target variable). The target variable contains 0 and 1 (1 represents fake comment ). We can use this project to anticipate and control misinformation in the Social media like Youtbe , Twitter , Instagram. I have used histogram for showing the visualization of length of comment to number of comments , Day wise total count of comment , Hour wise total count of comment , class wise comment. In pre-processing , I have convert all text lower , removing punctuation and stop words  Lemmatization used for morphological analysis of the words and it is necessary to have detailed dictionaries which the algorithm can look through to link the form back to its lemma for meaningful word in comments. I have used word vectorization for mapping words or phrases from vocabulary to a corresponding vector of real numbers which used to find word predictions in comments. I have tried number of models using different algorithms but accuracy of Decision tree Classifier (Accuracy : 93.53) , logistic regression (Accuracy : 89.22) , random forest (Accuracy : 87.06) is high so i choosed Decision tree Classifier for prediction.
