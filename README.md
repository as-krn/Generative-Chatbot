<h1>Generative Chatbot </h1>
<b>  The step sequence of Generative chatbot operation is as follows.</br>
1. Collection of data </br>
2. Preprocess </br>
3. Word Embedding </br>
4. LSTM(Long Short Term Memory) </br>
5. Seq2Seq Model </br>

# Collection of data
<b>Collecting data occupies a very important place in this project, as in every software project. A very large data set is needed to train a chatbot. Chatbots generally need conversational data because they want to reflect real-world interaction to users. We used podcasts and web scraping to create our own dataset.</br>

# Preprocess
<b>Preprocessing is a method of cleaning and modifying data and improving its quality. Preprocessing the data before entering it into the trainer increases the accuracy of the trained model. After receiving the data from two separate txt files, Questions and Answers, we process it using the functions of Python's Re (Regular Expressions/RegEx) library for preprocessing.</br>

# Word Embedding
<b>Computers only understand numbers. Therefore, the words that need to be presented to the machine must be expressed numerically. Word embedding is a natural language processing technique for representing words as numerical vectors. These vectors, which are initially represented by numbers independent of each other, become closer to the numerical values of vectors with similar meaning as they are trained with large text data sets. Thus, the meanings of words are represented in a lower dimension. In this way, ChatBot better understands the relationships between words and creates more logical sentences.</br>

# LSTM(Long Short Term Memory)
<b>Long Short Term Memory is an RNN (Recurrent Neural Network). Unlike classical RNN, memory blocks in LSTM handle long serial data better than RNN. LSTM's memory blocks include input gate, forget gate and output gate. These gates select between information, choosing which information will be discarded from the memory block (forget gate), added (input gate) or sent as output (output gate).</br>

# Seq2Seq Model
<b>Seq2seq or sequence-to-sequence; It is a machine learning model used in complex language problems such as creating content or text, translating between languages, answering questions, summarizing text and creating Chatbots. Seq2seq consists of Encoder and Decoder parts, each with at least one layer of LSTM.</br>
