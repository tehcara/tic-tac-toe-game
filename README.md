# Tic-Tac-Toe Game

An independent project demonstrating **GUI implementation**, **event-driven logic**, and **programmatic state management** in Python.

## Project Overview
Originally developed as a Command Line Interface (CLI) script, this program was refreshed in 2024 to a graphical environment using `Tkinter`. It uses a 3x3 game board and an automated (pseudo-random) opponent. (The computer opponent is really dumb! Play strategically and you should win easily.)

## Technical Highlights
* **Programmatic UI Generation:** Uses nested loops to generate a responsive grid layout, mapping button clicks to a backend dictionary state.
* **Win Condition Algorithms:** Implements a victory-check function that iterates through possible winning combinations using coordinate-matching logic.
* **Custom Styling & UX:** Leverages `ttk.Style` to provide visual feedback, differentiating player and computer moves through distinct colour-coding (blue versus red).
* **Defensive Logic:** Employs move validation to ensure computer moves are restricted to available spaces, maintaining system integrity.

## Tech Stack
* **Python** (Core Logic)
* **Tkinter / ttk** (GUI Framework & Custom Styling)
* **Random** (Pseudo-AI Opponent)
