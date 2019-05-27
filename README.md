# eebo_tcp_clean_text
Jupyter notebook to clean EEBO-TCP full-text document

Text cleaning notebook for Early English Books Online - Text Creation Partnership texts. Can be used as basis for cleaning any full-text document.

This is some amateurish Python 3 code to make EEBO-TCP texts more easily analyzed in Natural Language Processing (NLP), though most of the edits can be used on any text file. It is pretty basic, and is intended primarily for humanities-types who already know how to do the basics in Python, but who have trouble finding concrete examples of how to clean dirty text before the standard preprocessing of stemming/lemmatizing, stopwording...

Generally, the code requires you to:
1. Have a text file that you want to clean. This code has been run on several TCP texts, and uses Rohan's Compleat Captain (a 1640 edition of Caesar plus commentary) as an example. One could refactor it and make it run over a directory of text files.
2. Have installed the Python libraries used, primarily NLTK.

The notebook contains much (minute) discussion of the issues cleaning early modern English text, and the strategies I chose.
