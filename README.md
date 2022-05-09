# Language Translator using LSTM Architecture

For this project, we have used Neural Machine Translation (NMT). NMT utilizes artificial intelligence to learn and enhance the 
knowledge of that language (Austin, The Big Guide to Machine Translation). According to IBM Cloud Education, “Natural language processing (NLP) 
refers to the branch of computer science - and more specifically, the branch of artificial intelligence or AI - concerned with giving computers the 
ability to understand text and spoken words in much the same way human beings can”  (IBM Cloud Education, 2020). 

One of the main obstructions to natural language processing is the need for huge amounts of data to train the model. The earlier methods used in 
natural language processing used simple approaches in machine learning where the model is built to give certain specific responses to specific key words 
or phrases. But the approach of utilizing deep learning is more useful and easy to understand the intentions of the speakers by understanding huge 
amounts of data like how a child understands how to use human languages. 

Natural Language Processing (NLP) can be utilized to perform various tasks such as text classification, text extraction, machine translation and 
natural language generation. In Spite of all those advantages of NLP, it is facing many challenges such as collection of large amounts of data, 
precision in understanding the data, inability to interpret and understand the tone used in the language data and also the evolving use of language 
which produces new meanings and usages of words (Lutkevich, 2021).


In this project we used Long Short Term Memory (LSTM) Network architecture, which is a Recurrent Neural Network (RNN). 
This network can preserve the knowledge and is capable of dealing with the vanishing gradient problem faced by RNNs. 
LSTM networks are specifically created to evade the long-term dependency drawback. 
The LSTM consists of three divisions inside it, the first one deals with whether to remember the data or the data is insignificant for remembering. 
The second division tries to absorb the information from the incoming data. While the third division sends the upgraded information to the next cell. 
The first division is called the Forget Gate, the second division is called the Input Gate and the third division is known as the Output Gate. 
The LSTM network also has the hidden and cell states. Here the short-term memory is the hidden state while the long-term memory is the cell state 


For algorithm and approach, We are using a sequence to sequence modeling technique with Long Short Term memory networks by cleaning the data, tokenizing, 
        padding, modeling, embedding, encoding and decoding to create a language translator. As far as our framework is concerned we use 
        Keras as the frontend and Tensorflow for the backend. We have a multi-classification model using LSTM which is the perfect algorithm for 
        language translation as it prevents vanishing gradients. Our algorithm needs a large amount of training data compared to other approaches but 
        luckily our german_sample.txt is large enough. The algorithm has the ability to remove or add information by structured call gates. 
        These gates are composed of sigmoid neural net layer and pointwise multiplication operator. The sigmoid layer produces a number of 0 and 1, deciding 
        how much of each component should be let through. So if the value is 0 nothing is let through but if the value is 1, everything is let through. 
        The outputs for the algorithm are assigned probability for each class, which can be used to reduce the number of false positives using threshold.
    
    
