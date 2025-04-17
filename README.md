🎨 Colored Square Game
A simple terminal-based guessing game written in C++. The program randomly selects a color, and the player must guess it from a list of predefined options.

🕹️ Gameplay
The game randomly chooses one of five colors:

Red

Green

Blue

Yellow

Purple

Your task is to guess which color the game has chosen. The game continues in a loop until you guess the correct color.

📋 Features
Random color selection using rand()

Case-insensitive user input

Basic input validation

Console screen clearing with system("cls") (Windows only)

Pause between guesses with Sleep(1000) (1 second delay)

🧱 Requirements
Windows OS (uses windows.h and system("cls"))

C++ Compiler (e.g., g++, MSVC)

🚀 How to Run
Compile the code
Open Command Prompt and compile the file with your C++ compiler:
g++ -o ColorGame ColorGame.cpp

Run the game
./ColorGame

3.Guess the color!

🛠️ Notes
This game is case-insensitive. You can type colors in any case (e.g., Red, rEd, RED).

The screen clears after each guess for a cleaner interface.

Works on Windows only due to windows.h and system("cls").

Sample Output 
Welcome to the Colored Square Game!
Guess the color of the square (Red, Green, Blue, Yellow, or Purple).
Enter your guess: blue
Wrong guess. Try again!

📄 License
This project is open source and free to use. Modify it however you like!




