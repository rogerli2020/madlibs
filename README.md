# MAD LIBS

## GENERAL INFORMATION
<b>IMPORTANT: This program is only compatible with Python 3 </b>

This program is written for the purpose of practicing basic Python skills, such as opening and modifying a text file, string concatenation, object oriented programing, and decomposition.

---
## PROGRAM DESCRIPTION
This program is intended work as a text-based Mad Libs game. The overall sequence of what should be happening in this program is listed as follows:
1. player(s) will be welcomed with a welcome message
2. player(s) will be asked to enter the total number of player(s) involved
3. player(s) will be asked to enter their name(s)
4. player(s) will be asked to select a blank paragraph either randomly or manually.
5. if player(s) choose to select a blank paragraph randomly, the game will start immediately with a randomly chosen paragraph.
6. if player(s) choose to select a paragraph manually, the game will print all existing paragraphs inside the given text file (wordbank/paragraphs.txt). During this selection process, users also have the choice to modify (such as adding new lines, deleting existing lines) the given list. After a paragraph is selected, the game will start.
7. player(s) will be asked to fill the line using a randomly generated word bank that is unique to each player.
8. a vote will be called.
9. each player will vote for the player who has the filled paragraph they like the most.
        - a player can vote for themself.
10. the player(s) who gained the most votes win(s) the game.
        - if more than one player are involved in the game, more than one player can win the game.
11. the player(s) will be asked if they want to play again.
12. if yes, the player(s) will then be asked if they want to play with the same player(s)

---
## CONFIGURATION
- This program needs at least one word bank text file, only one sample paragraphs and only one recovery text file to run properly.
- Edit the "FILE_LOCATIONS" list, the "PARAGRAPH_LIST_LOCATION" string, or the "RECOVER_LIST_LOCATION" string to change the respective .txt file location.
