# AutoFlashcardQuizletCreator

The aim of the project is to facilitate the creation of Flashcards using the Quizlet website. Searching the internet I found that there is no such program and creating fiches for learning English is a breakneck job that can often take many hours. This programme can speed up the process considerably without much effort just by writing the vocabulary you want to translate.

# Acquisition of definitions and examples

The first file called [1 Cambridge webscraping.ipynb](https://github.com/Jkfre247/auto-flashcard-Quizlet-creator/blob/main/1%20Cambridge%20webscraping.ipynb) loads our txt file in which we have our vocabulary. In my case the txt file is called [words.txt](https://github.com/Jkfre247/auto-flashcard-Quizlet-creator/blob/main/words.txt). It goes through each word available extracting the definition and usage examples from the cambridge dictionary using the scraping process. All depending on the availability and correctness of the word. If the word is entered correctly it will retrieve the definition and examples. We get a finished file which will be used in the second section [gotowy.csv](https://github.com/Jkfre247/auto-flashcard-Quizlet-creator/blob/main/gotowy.csv).

# Creating flashcards
A second file is used to create the fiches [2 Quizlet creating flashcards.ipynb](https://github.com/Jkfre247/auto-flashcard-Quizlet-creator/blob/main/2%20Quizlet%20creating%20flashcards.ipynb) In this file, the program goes through a couple of steps
* Logging in to the platform (really good security).
* Entering the tab where you create flashcards
* If there is a notification that prevents it from continuing to function (quizlet premium advertising) will close it. (Be aware that the id may change so this element may change).
* Creation of a title and description
* Create as many blank cards as our number of words
* Filling the flashcards with a word and on the other side a definition with examples the definition is in "[]" the examples are in "()"
* Pressing the Create Flashcards button
# Instruction
1. create your own list of vocabulary/phrases in a txt file. Each item should be on a separate line
2. run file one using anaconda or vscode [1 Cambridge webscraping.ipynb](https://github.com/Jkfre247/auto-flashcard-Quizlet-creator/blob/main/1%20Cambridge%20webscraping.ipynb)
3. Setting the name of the wordlist variable with the name of our txt file. If you wish, you can rename the csv file
4. Activation of all code blocks
5. Starting file [2 Quizlet creating flashcards.ipynb](https://github.com/Jkfre247/auto-flashcard-Quizlet-creator/blob/main/2%20Quizlet%20creating%20flashcards.ipynb)
6. Assigning appropriate values to the login and password variables and to the wordlist variable assigning the name of your csv file
7. Run all code blocks congratulations your flashcards should be created
Note there may be an error related to the change of security accordingly in which case you have to find the element in question and swap it with the correspondingly found element. The programme is working correctly as of 28.02.2023
