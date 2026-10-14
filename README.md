# Guessing Game in C++

A simple number guessing game developed in C++ as part of my programming studies at Alura.

## About the Project

The goal is to guess a randomly generated secret number between 0 and 99. The player can choose a difficulty level, which determines the number of available attempts.

The game also provides hints indicating whether each guess is higher or lower than the secret number. At the end, the player receives a score based on their guesses.

## Features

- Three difficulty levels: Easy, Medium, and Hard.
- Randomly generated secret number.
- Hints after each guess.
- Limited attempts depending on the selected difficulty.
- Score calculation based on guessing accuracy.

## Technologies

- C++
- Standard Library (`iostream`, `cstdlib`, and `ctime`)

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/eduardo-heck/guessing-game-cpp.git
cd guessing-game-cpp
```

### 2. Compile the program

Using `g++`:

```bash
g++ jogodaadvinhacao.cpp -o guessing-game
```

### 3. Run the game

On Windows:

```bash
.\guessing-game.exe
```

On Linux or macOS:

```bash
./guessing-game
```

## What I Learned

- Using conditional statements and loops in C++.
- Generating random numbers.
- Handling user input.
- Implementing a scoring system.
- Working with Git and GitHub.

---

Developed by [Eduardo Heck](https://github.com/eduardo-heck).