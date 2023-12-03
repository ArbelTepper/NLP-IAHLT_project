# NLP-heb_conullu_exploration
Exploring and visualizing CONULLU files in Python

Using the IAHLT CONLLU tageged Hebrew sentences corpus, I created a program that reads the file using the pyconll library.
Through a costum object I made - "token_dictionary", I was able to create a dataframe which holds a frequency dictionary of all the words in the corpus which have the same "POS" and "relation" properties.

The token_dictionary has various methods that allow for interesting data extractions and visualizations.
