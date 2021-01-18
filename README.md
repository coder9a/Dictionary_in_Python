# Dictionary_in_Python
We are going to build an Interactive Dictionary which lets users search the desired word and its meaning and also provides the aptest word suggestion in case of misspelling or mistype by user.
We need to perform following steps to make our Dictionary Application:
Load JSON file into python.
Ask the user for a Word.
Pass that word into a word_meaning() function where the code will be looking for the meaning of input word into the words.json file.
word_meaning() function will not just look for the meaning into words.json file but also analyze the word to check if a user somehow mistypes the word and meant something else, which will be making our dictionary interactive.
We have used get_close_matches() function of difflib module inside word_meaning() function to analyse the word and making our application interactive, difflib module provides classes and functions for comparing sequences.
get_close_matches: Return a list of the best ‘good enough’ matches. Word is a sequence for which close matches are desired (typically a string), and possibilities is a list of sequences against which to match word (typically a list of strings).
