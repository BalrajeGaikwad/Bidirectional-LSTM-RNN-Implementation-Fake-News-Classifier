**📌 Project Description: Bidirectional LSTM RNN – Fake News Classifier**
This project demonstrates the implementation of a Fake News Detection system using a Bidirectional Long Short-Term Memory (BiLSTM) based Recurrent Neural Network (RNN). The aim is to classify news articles or headlines as real or fake using Natural Language Processing (NLP) and deep learning techniques.

**🔍 Objective:**
To build an intelligent model that can learn contextual word relationships in text data and effectively detect misleading or fabricated news content.

**🧠 Key Features:**
**Data Preprocessing:**
- Tokenization
- Stopword removal
- Text cleaning (punctuation, lowercasing)
- Lemmatization
- Padding sequences to uniform length
**Word Embedding:**
- Using Keras Embedding layer to convert tokens into dense vectors
**Deep Learning Model:**
- Architecture includes:
- Embedding layer
- Bidirectional LSTM layer
- Dropout for regularization
- Dense output layer with sigmoid activation for binary classification
**Model Evaluation:**
- Accuracy, precision, recall, F1-score
- Confusion matrix for performance interpretation

**🧾 Technologies Used:**
- Python
- TensorFlow / Keras
- NLTK (Natural Language Toolkit)
- NumPy / Pandas
- Matplotlib / Seaborn (for visualization)

**💡 Use Cases:**
- Social media monitoring
- News aggregator filtering
- Media outlet credibility checks
- Educational demonstrations for NLP and deep learning
