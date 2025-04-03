# Inscryption-Inspired Card Game

Welcome to our **Inscryption-Inspired Card Game** repository! This is a work-in-progress project developed by me and my peer, **MrFairbunkle**, inspired by the card-based mechanics and eerie aesthetic of *Inscryption*. We’ve been building this game collaboratively, with most edits and contributions made on MrFairbunkle’s local device, though I’ve been actively involved in its design and development.

## About This Project

This game is a digital card game built with Python and Pygame, featuring a variety of animal-themed cards with unique stats (health, attack, blood, and bones). Players can draw a hand of cards, view their details, and place them onto a play area. It’s an early prototype, focusing on card rendering and basic interaction, with plans to expand into a full-fledged strategy game.

### Collaboration Note
- **Development Process**: Most code changes and commits have been made on MrFairbunkle’s local machine, so my contributions may not be as visible in the commit history. However, we’ve worked closely together on planning, coding, and testing.
- **Inspiration**: Drawn from *Inscryption*’s unique blend of card mechanics and atmospheric design.

## Features
- **Card System**: Over 30 unique cards (e.g., "BulletAnt," "PerryThePlatypus") with stats for health, attack, blood, and bones.
- **Dynamic Card Display**: Cards show their name, stats, and a thumbnail image (with fallback for missing images).
- **Player Hand**: Randomly generates a 5-card hand at the start.
- **Interactive Play Area**: Drag cards from your hand to one of five orange play squares.
- **Hover Effects**: Cards lift slightly when hovered over with the mouse.
- **Fullscreen Mode**: Runs in fullscreen using the user’s native screen resolution.
- **Controls**:
  - `W`: Move hand up.
  - `S`: Move hand down.
  - `Escape`: Quit the game.
  - Left-click: Select and place cards.

## Files Included
- `main.py`: The core Python script with Pygame logic for the game.
- `assets/inscryptioncard.jpg`: Base card template image.
- `assets/table.jpg`: Background table image.
- `card_thumbnail/`: Folder containing card-specific images (e.g., `bulletant.jpg`, `perrytheplatypus.png`).

*(Note: Ensure all image assets are present in the correct directories for the game to run properly.)*

## How to Run
1. **Prerequisites**:
   - Python 3.x installed.
   - Pygame library: Install via `pip install pygame`.
2. **Clone the Repository**:
   ```bash
   git clone https://github.com/charlierobertsuk/inscryption-game.git
   ```
3. **Set Up Assets**:
   - Place `inscryptioncard.jpg` and `table.jpg` in an `assets/` folder.
   - Add card images (e.g., `bulletant.jpg`) to a `card_thumbnail/` folder.
4. **Run the Game**:
   - Navigate to the project folder.
   - Execute `python main.py` in your terminal.
5. **Play**:
   - Use the mouse to hover over and select cards.
   - Click to move cards to the play squares.
   - Use `W`/`S` to adjust the hand position and `Escape` to exit.

## Current Limitations
- **Early Prototype**: Lacks full game mechanics (e.g., combat, turns, or win conditions).
- **Image Dependency**: Missing card images result in a red placeholder square.
- **Basic Interaction**: Only card placement is implemented; no gameplay logic yet.
- **Single-Device Edits**: Most development occurred on MrFairbunkle’s machine, limiting my visible contributions in this repo.

## Next Steps
- Add combat mechanics between placed cards.
- Implement turn-based gameplay and opponent AI.
- Enhance card abilities (e.g., "BlackMamba" instant kills, "MimicOctopus" mirroring).
- Improve UI with a proper game board and resource tracking (blood/bones).
- Sync development across both our devices for better collaboration.

## Acknowledgments
- **MrFairbunkle**: My co-developer and collaborator, who’s hosted most of the coding sessions.
- **Inscryption**: The game that inspired us to explore card-based mechanics in Python.
