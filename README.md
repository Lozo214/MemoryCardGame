# Memory Card Game

A desktop memory matching game built in Java using JavaFX. Players flip cards to find matching pairs while tracking score and performance across different themes and difficulty levels.

## Preview

### Welcome Screen
![Welcome Screen](path/to/your/screenshot.png)

### Demo Videos
- [Gameplay Demo 1](link-to-video-1)
- [Gameplay Demo 2](link-to-video-2)


## Features
- JavaFX graphical user interface
- Multiple card themes
- Multiple difficulty settings
- Animated card flipping
- Sound effects and background music
- Persistent high-score tracking
- Object-oriented design with separate game logic and stats management
- JUnit test files for core components

## Tech Stack
- Java
- JavaFX
- JUnit

## Project Overview
This project is a card-based memory game where players reveal cards two at a time and try to match all pairs using the fewest possible attempts. The game includes visual and audio enhancements, theme and difficulty selection, and saved statistics to improve replayability and user experience.

## What I Learned
Through this project, I practiced:
- object-oriented programming in Java
- GUI development with JavaFX
- event-driven programming
- animation and user interaction design
- file handling / object serialization for saved stats
- testing core game components

## How to Run
1. Clone the repository.
2. Open the project in your Java IDE.
3. Make sure JavaFX is installed and configured.
4. Run the main game file:
   `MemoryGame_GUI.java`

## Project Structure
- `MemoryGame_GUI.java` - JavaFX interface and gameplay flow
- `MemoryGame.java` - core game logic
- `Card.java` - card representation
- `Deck.java` - deck generation and card management
- `Stats.java` - score/stat tracking and persistence
- `CardTest.java`, `DeckTest.java`, `MemoryGameTest.java`, `StatsTest.java` - test files

## Future Improvements
- Add more card themes
- Improve game UI styling
- Add timer-based game modes
- Add leaderboard enhancements
- Package as a runnable application
