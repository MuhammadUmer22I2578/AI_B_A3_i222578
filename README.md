# AI_B_A3_i222578
Database Management System for Players and Games

This C++ program provides a simple database management system for managing players and games. The program uses binary search trees to store and organize data on players and games, allowing for efficient data manipulation. Users can insert, search, and save data, and associate games with players.

Features:
Insert Player: Add new players with unique IDs.
Insert Game: Add new games with unique IDs.
Add Game to Player: Associate an existing game with a player by their IDs.
Search Player: Look up a player by their unique ID.
Search Game: Look up a game by its unique ID.
Save Player Data: Save all player information to a specified file.
Save Game Data: Save all game information to a specified file.
Show N Layers: Display the first N layers of players in the tree.
Show Layer Number: Find and display the layer number of a specific player by ID.
Show Preorder Path: Display the preorder traversal path to a player by ID.
Load Data on Startup: Automatically load data from `Players.txt` and `Games.txt` files.

File Structure:
Playes.txt: Stores player data in the format: Player ID, Name, Phone Number, Email, Password.
`0291782995,Misty Payne,032937458834,0291782995@nu.edu.pk,Qux0dcySTm 0312441589,John Doe,032184516789,johndoe@nu.edu.pk,Abcd1234`
Games.txt: Stores game data in the format: 
Game ID, Name, Developer, Publisher, File Size (in GBs), Downloads.
`3468322375,Stardew Valley,CraigJohnson,Byrd LLC,82.03,4171898 3584218103,Evil Dead The Game,Fox PLC,Long Johns and Blackburn,4.49,4197659`

Usage:
1.	Compile the code
2.	Run the compiled executable
3.	Follow the menu options to perform various operations on the player and game databases.

Functionality Breakdown:
•	Binary Search Tree Structure: Both PlayerTree and GameTree classes use binary search trees for efficient data storage and retrieval.
•	Game-Player Association: Games are associated with players through pointers, allowing each player to maintain a list of games they have played.
•	Layer Display and Path Tracing: Display functionality shows specific layers and the path to a player in preorder traversal.

Menu Options:
The menu presents the following options:
1.	Insert Player: Adds a new player to the database.
2.	Insert Game: Adds a new game to the database.
3.	Add Game to Player: Links an existing game to a player by ID.
4.	Search Player: Searches for a player by ID.
5.	Search Game: Searches for a game by ID.
6.	Save Player Data: Saves the player tree data to players.txt.
7.	Save Game Data: Saves the game tree data to games.txt.
8.	Show N Layers: Displays the specified number of tree layers for players.
9.	Show Layer Number: Shows which layer a player ID is on.
10.	Show Preorder Path: Shows the preorder path to a player ID.
11.	Exit: Exits the program.

Requirements:
•	C++ compiler
•	Files Players.txt and Games.txt in the same directory as the executable.

Implementation Notes:
•	The program does not use the <random>, <vector>, <algorithm>, <queue>, or <stack> libraries as per the design preferences.
•	Binary search trees ensure efficient O(log n) time complexity for search, insert, and save operations.

Known Limitations:
•	Console Input Only: All operations must be done via the console menu; no GUI support is provided.

Future Improvements:
•	Implement additional functionalities, such as updating player or game information and removing entries.
•	Enhance error handling for file operations and input validation.

License:
This project is licensed under the FAST NUCES. Feel free to use.
________________________________________
Thank you for using the Database Management System for Players and Games!

