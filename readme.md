Convert the Dutch macOS dictionary to StarDict
===============================================

To use the macOS dictionary with KoReader it needs to be converted to the 
StarDict format. 

1. Find the Dutch.dictionary, for example lookup a word and inspect the process
with Activity Monitor and look at the open files. 

2. Use [pyglossary](https://github.com/ilius/pyglossary) to convert to StarDict.

3. Ensure all files are called the same (e.g. dutch.\*) and include the
dutch.css from this file to style the result.



