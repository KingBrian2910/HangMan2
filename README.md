# HangMan2

Welcome, thank you for taking a look at ourprogram.

This program is a university project of ours whose requirements states the use of arrays and "user friendly" is a mandatory.

Brief description:
This program as stated before is hangman game designed for our university project. How we designed the program is based on the uses and utility of array, multidimensional array, and other functions such as rand, etc.

Randomizing the words : We randomize he word chosen from the library we created by using the function rand, limiting it to a maximum number of 10 and using switch to choose from the number ofwords taken from the library. The library is already set by ourselves and is in the file type .txt. Using this filetype, we can easily read the contents of the using fopen() and fscanf().

Checking the user input wrether is it right or wrong : Using a multidimensional array, we can check wrether the user has inputed the right word or not. How this works is by is by setting the coloumn of the multidimensional array sets as whole alphabet and the row is the number ofletters are in the word chosen. As the user inputs a the letter, the program will check each row to see if the letter matches the letter present in that row. There will be a finite number of chances for the user to try and if the user did, not complete the word, they will be given the option to try again.

Score : The score is based on how many mistakes the user made. maximum score of 600000 and will decrease by 100000 every time the user made a mistake until it reaches 0. in the menu section, users can look to see who has obtain the highest score during the game. this is done by having the program write the final score into a txt. file using fputs() and will read it using fopen() and fcanf().
