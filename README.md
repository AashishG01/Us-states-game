# Us-states-game
US States Game
Overview
The US States Game is an interactive, educational game built using Python's Turtle graphics library. The objective of the game is to correctly guess all 50 US states. As you guess each state, its name will appear on the map in its correct location. This game is a fun way to test and improve your knowledge of US geography.

Features
Interactive Map: A blank map of the United States is displayed, and players can guess the names of the states.
Progress Tracking: The game keeps track of the number of correctly guessed states.
Exit and Save Feature: Players can exit the game at any time, and the names of the states they haven't guessed yet will be saved in a CSV file for future reference.
Getting Started
Prerequisites
Python 3.x installed on your machine.
The following Python libraries are required:
turtle (usually included with Python)
pandas (for handling data)
csv (for saving data)
You can install Pandas using pip:

bash
Copy code
pip install pandas
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/aashishg01/us-states-game.git
Navigate to the project directory:

bash
Copy code
cd us-states-game
Download the required files:

Ensure you have the blank_states_img.gif file (image of the US map) in the project directory.
Ensure you have the 50_states.csv file (contains the coordinates and names of the states).
Run the game:

bash
Copy code
python main.py
How to Play
The game will display a blank map of the United States.
A text box will appear, prompting you to guess the name of a US state.
If you guess correctly, the state’s name will appear on the map at its correct location.
The game continues until all 50 states are correctly guessed or you choose to exit.
If you exit the game, a CSV file (left_state.csv) will be generated, listing the states you haven't guessed yet.
Future Improvements
Adding hints or clues for states that are difficult to guess.
Implementing a scoring system to rank player performance.
Including a timer to make the game more challenging.
Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions that improve the functionality or user experience are highly appreciated!

License
This project is licensed under the MIT License - see the LICENSE file for details.
