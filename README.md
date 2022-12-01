# lost-n-found
A project I'm working on for the first project of Codecademy's Computer Science Course.


This code is for the Final Project of CS101 Introduction to Programming. I chose to make a sort of text-based adventure, and lost-n-found was the game I came up with.
The code itself is comprised of three Classes, which bounce information back and forth as needed. Class Find_It, Interact, and Overlay.

Class Find_It consists of three functions to start the game, and one to act as a sort of while statement. Function space_saver in particular was made to ask a question regarding the in-game "map" (ASCII art that could make it tiresome to look through the console) if it should appear or not. Originally this function existed in Class Interact as part of both functions option_1 and option_2, but was consolidated in Find_It to save space. The other functions have roles accordingly, namely labeling both what is missing and where it is found, and the springboard to the oher classes from there.

Class Interact has two functions, option_1 and option_2. Option_1 is the function name for typing "interact" in the terminal, and is the overall function used to complete the game. Option_2 is the function name for typing "talk" and is flavor text to add to the game. It is meant to enhance the experience through a character interaction, and while it does not effect gameplay, it was inserted to give more personality to the game.

Class Overlay gives the interface for the player to use. The first screen shown to the player includes the "map", ASCII art made to show both the options for the player to continue the game (interact and talk) and a room that does show all the areas for the player to search.  Both functions main_screen and main_screen_deprecated have the same impact on the code, but exist separately to smooth gameplay. Additionally, function winnings gives the option to play again, and if the player types no, it will end the code there. If the player says yes, it will go through Find_It's three starting functions again, allowing an easy way to continue.

Warning about the game, is that it is completely random where the item is hidden, and it is basically a guessing game to find where it is. Perhaps, in the future, it can be improved, giving hints as to where the item could be hiding, but all ideas I had to implement this were very large (like making different versions of the ASCII art) meaning that it would make the code's size very large.

Thank you for reading and enjoy!
