# Word_do_Word
This gem is designed to work with text files of the format.txt 
The main task is the frequency analysis of text files. The input is provided with the path to the folder with the files in the format.txt, and returns us a list of words found in the files, indicating the number of occurrences for each word. There is also a stop list of words (words that are not taken into account when counting), and lemmatization.

## Author 
Author::    Egor Voronin
Copyright:: Copyright (c) 2024 The MehMat.
License::   MIT

## class Wordling
This class contains methods for working with text files.

## Methods
Public:
def initialize(stop_words: [], lemmatization: false)
def analyze_folder(folder_path, filename_pattern = '*')

Private:
def extract_words(file)
def lemmatize(word)

## Detailed description

### def initialize(stop_words: [], lemmatization: false)
A public method that declares class fields. 

params:

stop_words is a list of words that will not be counted.
lemmatization is the flag of lemmatization of our words.

### def analyze_folder(folder_path, filename_pattern = '*')
A public method that counts words.

params: 

folder_path is the path to the directory where the words in .txt files will be counted.

filename_pattern is a pattern set as a regular expression that will analyze those files whose name matches this pattern. 
The default is '*' (i.e. all files are analyzed).

return:
We get back a list of words found in the files, indicating the number of occurrences for each word.