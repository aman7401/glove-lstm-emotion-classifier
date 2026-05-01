# Emotion-Detection-From-Text-or-Paragraph
TCS Remote Internship (Emotion Detection From Text or Paragraph)

Automate detection of different emotions from textual comments and feedback

Collaborators
Name	        Email-id

Name of the Company 	         TCS iON
Name of the Industry Mentor 	 Mr. Debashis Roy
Name of the Institute 	       Institute of Engineering & Management  Kolkata

Project Synopsis
Title of the project       Automate Detection of different emotions from textual comments and feedback   
Domain                     Artificial Intelligence (AI)/ Machine Learning, Deep Learning

Objective/Aim
Social media is growing as a communication medium where people can express online their feelings and opinions on a variety of topics in ways they rarely do in person. Detecting sentiments and emotions in text have gained considerable amount of attention in the last few years.

Technical Details

We use word and document embeddings and a set of semantic features and apply CNN-LSTM and a fully connected neural network architectures to obtain performance results
This study proposes a long-short term memory (LSTM)-based approach to text emotion recognition based on semantic word vector and emotional word vector of the input text. For each word in an input text, the semantic word vector is extracted from the word2vec model. Besides, each lexical word is projected to all the emotional words defined in an affective lexicon to derive an emotional word vector. An autoencoder is then adopted to obtain the bottleneck features from the emotional word vector for dimensionality reduction. The autoencoder bottleneck features are then concatenated with the features in the semantic word vector to form the final textual features for emotion recognition.

Algorithms   

This project is about performing emotion detection from text using PyTorch. For this project, we implemented an NLP task of creating a model to detect the emotion from text. We developed this using the PyTorch library where we created our Deep Neural Network using GloVe Word Embeddings, LSTMs and fully connected layers.
We will build an LSTM model that takes as input word sequences that will take word ordering into account. We will use 50-dimensional GloVe pre-trained word embeddings to represent words. We will then feed those as an input into an LSTM that will predict the most appropiate emotion for the text.


REFERENCES
[1] A. Agarwal, B. Xie, I. Vovsha, O. Rambow, and R. Passonneau, “Sentiment analysis of twitter data,” in Proceedings of the workshop on languages in social media. Association for Computational Linguistics, 2011, pp. 30–38.
[2] P. Ekman, “Facial expression and emotion.” American psychologist, vol. 48, no. 4, p. 384, 1993.
[3] F. Harrag, “Estimating the sentiment of arabic social media contents: A survey,” in 5th International Conference on Arabic Language Processing, 2014.
[4] M. Abdullah and M. Hadzikadic, “Sentiment analysis on arabic tweets: Challenges to dissecting the language,” in International Conference on Social Computing and Social Media. Springer, 2017, pp. 191–202.
[5] K. Shaalan, “Rule-based approach in arabic natural language processing,” The International Journal on Information and Communication Technologies (IJICT), vol. 3, no. 3, pp. 11– 19, 2010.
[6] Z. Eviatar and R. Ibrahim, “Why is it hard to read arabic?” in Handbook of Arabic literacy. Springer, 2014, pp. 77–96.
[7] C. Guggilla, T. Miller, and I. Gurevych, “Cnn-and lstm-based claim classiﬁcation in online user comments,” in Proceedings of COLING 2016, the 26th International Conference on Computational Linguistics: Technical Papers, 2016, pp. 2740–2751.
[8] Y. Kim, “Convolutional neural networks for sentence classiﬁcation,” arXiv preprint arXiv:1408.5882, 2014.
[9] S. M. Mohammad and S. Kiritchenko, “Understanding emotions: A dataset of tweets to study interactions between affect categories,” in Proceedings of the 11th Edition of the Language Resources and Evaluation Conference, Miyazaki, Japan, 2018.
[10] T. Mikolov, K. Chen, G. Corrado, and J. Dean, “Efﬁcient estimation of word representations in vector space,” arXiv preprint arXiv:1301.3781, 2013.
[11] S. M. Mohammad and F. Bravo-Marquez, “Wassa2017 shared task on emotion intensity,” arXiv preprint arXiv:1708.03700, 2017.
[12] F. Bravo-Marquez, M. Mendoza, and B. Poblete, “Meta-level sentiment models for big social data analysis,” KnowledgeBased Systems, vol. 69, pp. 86–99, 2014.
[13] S. Hochreiter and J. Schmidhuber, “Long short-term memory,” Neural computation, vol. 9, no. 8, pp. 1735–1780, 1997.
[14] Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner, “Gradientbased learning applied to document recognition,” Proceedings of the IEEE, vol. 86, no. 11, pp. 2278–2324, 1998.
[15] R. Plutchik, “Emotions and psychotherapy: A psychoevolutionary perspective,” in Emotion, psychopathology, and psychotherapy. Elsevier, 1990, pp. 3–41.


Links
https://medium.com/@sabber/classifying-yelp-review-comments-using-lstm-and-word-embeddings-part-1-eb2275e4066b#:~:text=Build%20a%20neural%20network%20with%20LSTM,-In%20the%20following&text=The%20network%20starts%20with%20an,word%20in%20a%20meaningful%20way.
https://github.com/krishnaik06/Word-Embedding/blob/master/Untitled2.ipynb
https://github.com/krishnaik06/Natural-Language-Processing/blob/master/Toeknization.py
https://github.com/krishnaik06/Natural-Language-Processing/blob/master/Toeknization.py
https://ieeexplore.ieee.org/abstract/document/8614159
https://www.youtube.com/results?search_query=LSTm
https://github.com/krishnaik06/Word-Embedding/blob/master/Untitled2.ipynb
https://www.analyticsvidhya.com/blog/2020/03/pretrained-word-embeddings-nlp/
https://medium.com/@sabber/classifying-yelp-review-comments-using-cnn-lstm-and-visualize-word-embeddings-part-2-ca137a42a97d
https://medium.com/@sabber/classifying-yelp-review-comments-using-lstm-and-word-embeddings-part-1-eb2275e4066b#:~:text=Build%20a%20neural%20network%20with%20LSTM,-In%20the%20following&text=The%20network%20starts%20with%20an,word%20in%20a%20meaningful%20way.
https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa
https://towardsdatascience.com/light-on-math-ml-intuitive-guide-to-understanding-glove-embeddings-b13b4f19c010
https://github.com/krishnaik06/Natural-Language-Processing/blob/master/Toeknization.py


