# OOP-GSLC-WORDLE-ON-JAVA
Wordle is a game from the website https://www.nytimes.com/games/wordle/index.html. It is a game about guessing words given randomly daily.

For this GSLC assignment I decided to recreate this game into a simple java program.
This program will pick a random number from 0 - 15 (the number of words currently implemented in the system) and choose the word within an array to be guessed by the player
The player needs to guess the word within 6 tries, while guessing the system will give the player some indicators such as G, Y, and X.
If the player guesses the correct word, the player wins. If the player fails to guess, the player loses.

Game Interface


![Interface](https://user-images.githubusercontent.com/127413800/224049424-d46bac00-f359-4c9e-9021-1c745e66401b.png)


Win Interface


![WIN](https://user-images.githubusercontent.com/127413800/224052442-bf882d3d-7d86-4580-b0df-1ae86599abd4.png)



Lose Interface


![LOSE](https://user-images.githubusercontent.com/127413800/224052430-e19c2b4c-2278-462f-8bda-f71d3f9ea3f8.png)

# Array Usage
Array is used to store the words, in this case there are 15 words that is stored, so the index is between 0 - 14

# Method usage
Method is used to count how many correct words in the correct position, example if there is 5 it will output 5 hence the word is correct.
