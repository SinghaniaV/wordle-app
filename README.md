# Wordle Game

## Overview

This project is a command-line implementation of the popular word puzzle game **Wordle** in Python. The game challenges the player to guess a five-letter word within six attempts. After each guess, the game provides feedback on which letters are correct, in the correct position, or present in the word but in the wrong position.

## Features

- **Interactive Gameplay**: Play the game directly from your terminal or command line.
- **Feedback Mechanism**: After each guess, the game highlights:
  - Letters in the correct position.
  - Letters present in the word but in the wrong position.
  - Letters not present in the word at all.
- **Random Word Generation**: The game selects a random word from a predefined list for each new game session.
- **Win/Loss Conditions**: The player wins if they guess the correct word within six attempts. After six incorrect attempts, the game reveals the word.

## Getting Started

### Prerequisites

To run this game, you need to have Python installed on your machine. This project is compatible with Python 3.x.

### Setup

   ```bash
   git clone https://github.com/SinghaniaV/wordle-app

   cd wordle-app

   pip install -r requirements.txt

   python play_wordle.py
