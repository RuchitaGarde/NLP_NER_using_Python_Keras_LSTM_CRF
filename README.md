# NLP_NER_using_Python_Keras_LSTM_CRF
Natural Language Processing.
Named Entity Recognition (NER) using Conditional Random Field (CRF) & LSTM (Recurrent Neural Network)

This dataset is extracted from GMB(Groningen Meaning Bank) corpus which is tagged, annotated and built specifically to train the classifier to predict named entities such as name, location, etc.

## BIO scheme
All the entities are labeled using the BIO scheme, where each entity label is prefixed with either B or I letter. B- denotes the beginning and I- inside of an entity. The words which are not of interest are labeled with 0 – tag.
Below table shows the detailed information about labels of the words.
| Labels  |  Labels Meaning | Example  |
|---|---|---|
| geo | Geographical Entity | Dubai |
| org | Organization | New York Times |
| per | Person | Harry |
| gpe | Geopolitical Entity | European |
| tim | Time Indicator | Friday |
| art | Artifact | Economics |
| eve | Event | Olympic  |
| nat  | Natural Phenomenon  | Hurricane  |
| O | Other  | of, an, the  |

## POS Tag
As per information provided on [GMB site!](http://www.let.rug.nl/bjerva/gmb/manual.php), they use POS tagset which is a slight variant of the [Pen Treebank tagset!](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html!)
Number
Tag
Description
1.	CC	Coordinating conjunction
2.	CD	Cardinal number
3.	DT	Determiner
4.	EX	Existential there
5.	FW	Foreign word
6.	IN	Preposition or subordinating conjunction
7.	JJ	Adjective
8.	JJR	Adjective, comparative
9.	JJS	Adjective, superlative
10.	LS	List item marker
11.	MD	Modal
12.	NN	Noun, singular or mass
13.	NNS	Noun, plural
14.	NNP	Proper noun, singular
15.	NNPS	Proper noun, plural
16.	PDT	Predeterminer
17.	POS	Possessive ending
18.	PRP	Personal pronoun
19.	PRP$	Possessive pronoun
20.	RB	Adverb
21.	RBR	Adverb, comparative
22.	RBS	Adverb, superlative
23.	RP	Particle
24.	SYM	Symbol
25.	TO	to
26.	UH	Interjection
27.	VB	Verb, base form
28.	VBD	Verb, past tense
29.	VBG	Verb, gerund or present participle
30.	VBN	Verb, past participle
31.	VBP	Verb, non-3rd person singular present
32.	VBZ	Verb, 3rd person singular present
33.	WDT	Wh-determiner
34.	WP	Wh-pronoun
35.	WP$	Possessive wh-pronoun
36.	WRB	Wh-adverb


## Dataset
https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus?select=ner_dataset.csv

## References:
https://www.aitimejournal.com/@akshay.chavan/complete-tutorial-on-named-entity-recognition-ner-using-python-and-keras
https://github.com/Akshayc1/named-entity-recognition/blob/master/NER%20using%20CRF.ipynb
