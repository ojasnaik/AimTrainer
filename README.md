# Aim Trainer

Welcome to **Aim Trainer**, the perfect tool to enhance your aiming skills! Designed with simplicity and efficiency in mind, Aim Trainer provides a dynamic environment to practice your mouse aiming accuracy and speed.

## Game Overview

Aim Trainer challenges players to hit as many targets as possible within a set time limit. Each target appears as a circle that randomly spawns across the screen. The objective is to hit these circles as quickly and accurately as you can before the time runs out. Every successful hit plays a sound and triggers a visually satisfying burst animation. The game records the number of successful hits and displays your score at the end of each round.

## Features

- **Dynamic Target Spawning**: Targets appear at random positions on the screen, ensuring a varied experience each time you play.
- **Responsive Burst Animations**: Enjoy immediate feedback with a burst animation upon successfully hitting a target.
- **Score Tracking**: Keeps track of your hits and displays your score at the end of each session.
- **Adjustable Difficulty**: You can start the game with a different number of targets by clicking different areas of the start screen.

## Technologies Used

- **Pygame**: A powerful cross-platform set of Python modules designed for writing video games. Pygame provides the functionality to create the game window, handle user input, and render graphics.
- **Python**: All game logic is written in Python, making the code easy to modify and understand.
- **asyncio**: Used to manage asynchronous operations within the game, providing smoother gameplay and better handling of events.
- **WebAssembly (via Pygbag)**: For web-based deployments, the game utilizes Pygbag to compile the Python code to run efficiently in web browsers.

## Setup and Installation

### Requirements

- Python 3.x
- Pygame
- An internet connection for downloading dependencies

### Local Installation

1. **Clone the repository**:
https://github.com/ojasnaik/AimTrainer

2. **Navigate to the project directory**:
cd aim-trainer

3. **Install dependencies**:
pip install pygame

4. **Run the game**:
python main.py

### Playing the Game in a Web Browser

The game is also available to play in a web browser. Visit [http://aimtrainer.s3-website-us-east-1.amazonaws.com](#) to play the game online without any installation.

## How to Play

- **Start the Game**: Click on the left side of the initial screen for fewer targets, or the right side for more targets.
- **Aim and Click**: Use your mouse to aim and click on the targets.
- **Reset the Game**: Press 'R' to reset the game at any time during play.