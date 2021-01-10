Hi,
please find the details of the items under the folder

1.Intends.json:

Responses from the user and how to react for it,you can also modify the contents in the intents JSON file.

2.
Training.py:

contains the details for training the model and then saving the model which is to be used in an GUI.

3.Classes.pkl

pkl denotes pickle file...

what is a pickle file?
Pickling is a way to convert a python object (list, dict, etc.)

here in this project we have pickled classes and words so that it can be used in an GUI(i.e it can be used in another program)
contains the sub categories in intents.

4.words.pkl:
it contains the words after text processing i.e., stemming,lemmatisation etc.



how does this work?
in training.py ,from the intents.json it performs the basic NLP steps such as stemming,lemmatisation to identify unique words and categories,the words are then stored as words.pkl file and categories as classes.pkl,using these two pickle file a model will be created so that it can be used in another program,using these files the model will be trained and then to make it as user friendly a GUI is created which is in GUI.py


