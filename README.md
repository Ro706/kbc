# kbc

This is a C++ project that simulates the popular quiz show Kaun Banega Crorepati (KBC). The program asks the user a series of questions with four options each and awards points based on the difficulty level. The user can also use lifelines such as 50-50, audience poll, and expert advice.

## How to run

- Clone this repo using `git clone https://github.com/Ro706/kbc.git`
- Compile the kbc.cpp file using `g++ -o kbc kbc.cpp`
- Run the executable file using `./kbc`
- Enjoy the game and test your knowledge!

## Features

- The program has 15 questions of varying difficulty levels.
- The questions are randomly selected from a pool of 50 questions stored in a text file.
- The program keeps track of the user's score and displays it after each question.
- The program also shows the user the current question number and the amount they can win or lose.
- The user can quit the game at any time and take home the money they have won so far.
- The user has three lifelines that they can use once each:
  - 50-50: The program eliminates two wrong options and leaves only one correct and one incorrect option.
  - Audience poll: The program shows the percentage of votes for each option based on a random distribution.
  - Expert advice: The program shows the option that an expert (also randomly chosen) would choose.
