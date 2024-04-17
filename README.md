# POS-with-HMM
This project presents an implementation of POS tagging using the Hidden Markov Model, incorporating the Viterbi algorithm for efficient decoding. 

The system aims to assign the most probable sequence of POS tags to a given sentence by utilizing the probabilities of word sequences and their corresponding POS tags, computed through training. 

The implementation includes training the HMM on labeled data to estimate transition probabilities between POS tags and emission probabilities of words given their POS tags. The Viterbi algorithm is then applied to decode the most likely sequence of POS tags for a given input sentence, considering both transition and emission probabilities.
Through experimentation and evaluation on standard datasets, the performance of the HMM-based POS tagging system with the Viterbi algorithm is assessed. 


DATA: 
The dataset being used here is the Treebank corpus, which is a collection of manually annotated and tagged sentences from the Wall Street Journal.
Each sentence in the corpus is annotated with part-of-speech (POS) tags, indicating the grammatical category of each word.
The tags used in this corpus are based on the Universal POS tagset, which provides a standardized set of tags for POS tagging tasks across different languages.
