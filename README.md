# Spee-checker-For-Amharic-Languages

This Amharic spell checker uses a dual-input neural network architecture to predict and correct misspelled words based on their surrounding context. It leverages embedding layers to represent input tokens and employs bidirectional LSTM layers for effective context capturing from both left and right sequences. The model further refines the features through additional LSTM layers and merges the contextual information before making a prediction. Finally, a dense layer with a softmax activation outputs the most probable corrected word from the vocabulary.
