Implements the viterbi algorithm to find likeliest part-of-speech tag for a word.

    To run:
	$ python Viterbi_Tagger.py

This will train the model on the Brown corpus, then predict the POS tags for the sentences in the Brown development data. There will be three output files:

    trigrams.txt: a file containing all of the POS trigram probabilities in the corpus
    emissions.txt: a file containing all of the emission probabilities P(word | POS)
    tagged_sentences.txt: a file containing all of the sentences tagged by viterbi

The console will display the accuracy of the model compared to the tagged development data. Current state of the art POS taggers achieve ~97% accuracy, while this achieves an accuracy of 93.3%

The program runs in approximately 3 minutes. The code is based on an assignment in my Natural Language Processing class.
