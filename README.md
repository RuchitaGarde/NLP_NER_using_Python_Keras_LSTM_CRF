# NLP_NER_using_Python_Keras_LSTM_CRF
Natural Language Processing.
Named Entity Recognition (NER) using Conditional Random Field (CRF) & LSTM (Recurrent Neural Network)

This dataset is extracted from GMB(Groningen Meaning Bank) corpus which is tagged, annotated and built specifically to train the classifier to predict named entities such as name, location, etc.
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


## Dataset
https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus?select=ner_dataset.csv

## References:
https://www.aitimejournal.com/@akshay.chavan/complete-tutorial-on-named-entity-recognition-ner-using-python-and-keras
https://github.com/Akshayc1/named-entity-recognition/blob/master/NER%20using%20CRF.ipynb
