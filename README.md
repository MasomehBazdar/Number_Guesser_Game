# Number_Guesser_Game
Project: Number Guesser Game
Table of contents

Objective
Requirements
Tips
Solutions
Welcome to the Number Guesser Game project! This is a beginner-friendly Python project where you will build a fun game that challenges the user to guess a randomly generated number. For each incorrect guess, the user will receive hints to help them, but at the cost of reducing their final score.

Objective
Your task is to create a game with the following features:

The game generates a random number between a given range (e.g., 1 to 100).
The user is prompted to guess the number.
For each incorrect guess, the user receives a hint. The hint should indicate whether the actual number is higher or lower than the guessed number.
Each incorrect guess reduces the user's score.
The game ends when the user guesses the correct number or decides to quit.
Requirements
Organize your project with a clear directory and file structure.
Implement a scoring system.
Provide user-friendly messages and hints.
Ensure the user's input is validated.
Tips
Think about how you can break down the game into smaller components or modules.
Consider using functions or classes to encapsulate different functionalities.
Test each component separately before integrating them.
Solutions
Inside the Number Guesser Game Project directory, you will find two distinct solutions:

Solution A:

Pros:
Straightforward and simple structure.
Easy to understand for beginners.
Cons:
Lacks modularity, making it harder to maintain and expand.
All code is lumped together, which can be confusing as the project grows.
Solution B (Using the src pattern):

Pros:
Organized with all source code inside the src directory.
Modular design, separating different functionalities into distinct modules.
Includes a README.md for detailed explanations and a requirements.txt file to manage dependencies.
Cons:
Might be slightly more complex for absolute beginners.
Requires understanding of PYTHONPATH and Python packaging for optimal execution.
Might be Overkill: For very small projects or prototypes where rapid development is more crucial than organization, this approach can be excessive. For instance, if you're creating a quick script to automate a mundane task or a one-off data analysis, the overhead of setting up a modular structure might not be justified.
Good luck, and happy coding!