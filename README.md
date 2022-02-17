# NLP-TECH-GROUP6

NLP Technologies 
Assignment 1

Directory created by Sharona Badloe, Michiel van Nederpelt, Sezen Tuvay and Nihed Harrak.
Vrije Universiteit, Amsterdam The Netherlands. 
----------------------------------------------------------------------------------------------------------------

Project Description:
This notebook contains the code for extracting several syntactic features from the output of a dependency parser. 
The following features have been extracted:

- token_pos / token_tag: The part-of-speech tag of current token
- token_dep: Syntactic dependency, the relation between the current token and its head
- token_head: The head of the current token
- token_ent_type: The NER tag of the current token
- length_to_head: The distance between the current token and the head in integer
- path_to_head: The path from the current token to the head, displays all tokens in the path
- Children: The immediate syntactic dependents of the token
- Descendants: All descendents of the current token
- Ancestors: All ancestors of the current token
- Syntactic constituents: NLTK constituency tree 
- n-grams: token bigrams and trigrams
- previous and next tokens: token+1, token+2, token-1, token-2

REQUIREMENTS

- Python 3.7
- SpaCy 3.1.3
- NLTK 3.6.3

Downloads:

- Spacy library: https://spacy.io/usage
- NLTK library: https://www.nltk.org/_modules/nltk/downloader.html


How to run

This script has been created in Google Colab and exported to a notebook. 
The cells can be run in order of appearance. The output is already visible.
