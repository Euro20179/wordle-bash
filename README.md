# Wordle

![very nice](.assets/wojak.jpg)

Wordle clone in ***pure*** bash

# Install

* Youll need a list of words, my choice is `https://raw.githubusercontent.com/hghyug/english-words/main/words.txt`
* Use the `-f` option to specify the path to the words
  * Or edit the file so that the path to the list of words is correct
* Copy the file to somewhere in your `PATH`

# Usage

```
wordle [-ulLf]
Options:
	-L    length of answer word, default: 5
	-u    whether or not to use strictly bash (can be slow)
	-l    amount of lives, default: 5
	-f    specify a word list file, default: /home/euro/Documents/words.txt
```
