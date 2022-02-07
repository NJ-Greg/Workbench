This folder contains a simpleminded chess progam utilizing the python-chess package to allow
users to play chess in a Jupyter Notebook.  This is a modification of the file 
found [here](https://jupyter.brynmawr.edu/services/public/dblank/CS371%20Cognitive%20Science/2016-Fall/Programming%20a%20Chess%20Player.ipynb).

I had to implement some hacks because of issues with getting IPython.display.display to propery show 
a svg version of the board with a move prompt input box.

You will need an environment with Jupyter Lab and python-chess installed (that is a separate `pip install chess`, I did not include it in the conda .yml file here).

Example game pgn output:

[Event "Simple Jupyter Chess Game"]
[Site "?"]
[Date "2022.02.06"]
[Round "?"]
[White "Player"]
[Black "Random Legal Moves"]
[Result "1-0"]

1. e4 g5 2. Bc4 c5 3. Qf3 g4 4. Qxf7# 1-0

Exaple Final Position output.

![image](https://user-images.githubusercontent.com/64290138/152707406-a51c4840-af81-4663-970c-fcf6a0d1cee8.png)
