# NLP-assign1-q4
Datasets are A dataset and B dataset (this has the actual data). A dataset comprises of files sampled.txt, sampled.vocab.txt and samplet.text. The training data is found in the sampled.txt file and it contains the below:
 <s> a a b b c c </s> <s> a c b c </s> <s> b c c a b </s>

We are going to treat each line as a sentence. <s> is the start of sentence symbol and </s> is the end of sentence symbol. To keep the A dataset simple, characters a-z will each be considered as a word. i.e. The ﬁrst sentence has 8 tokens, second has 6 tokens, and the last has 7.

The ﬁle sampled.vocab.txt contains the vocabulary of the training data. It lists the 3 word types for the A dataset:

a 
b 
c
samplet.txt is the test corpus.

B dataset: The ﬁles train.txt, train.vocab.txt, and test.txt form a larger more realistic dataset. These ﬁles have been pre-processed to remove punctuation and all words have been converted to lower case. An example sentence in the train or test ﬁle has the following form:

<s> the anglo-saxons called april oster-monath or eostur-monath </s>
