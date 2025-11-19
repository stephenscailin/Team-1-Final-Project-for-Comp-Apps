# Resus Rush

Similar to Nintendo Game Overcooked or Hotel Rush, a player will have to manage the many tasks that one must do when a cardiac emergency patient goes into defibrillation. 

## Biomedical Context

This is a fun and educational game to teach individuals the clinical workflow during a cardiac emergency, with each level getting more complex. 

## Quick Start Instructions

### Opening the Repository in GitHub Codespaces
Opening the Repository in Github Codespaces
1. Click the green Code button at the top of this repository
2. Select "Create codespace on main"
3. Wait 1-2 minutes while GitHub builds the Codespace environment.
4. When it loads, you will see a full VS Code editor running in your browser.

### Running the Application

This project uses a simple static server to run the browser game.
	1.	In the Codespaces terminal, run: python3 -m http.server 8000
  2.	In the bottom panel of Codespaces, open the Ports tab.
	3.	Locate port 8000 → click Open in Browser.
	4.	The game will launch at:
http://localhost:8000/

You should now see the game canvas and be able to move your character
## Usage Guide

How to Play

This prototype simulates a mini “Overcooked-style” emergency room with three main stations:
	•	CPR Station (Orange)
	•	Pulse Check Station (Blue)
	•	Shock Station (Red)

Your goal is to complete all three steps in order before the timer reaches zero.

⸻

Step-by-Step

Step 1 — Move Your Character
	•	Use WASD or Arrow Keys to walk around the room.
	•	Your character is the yellow square on the canvas.

Step 2 — Start CPR
	•	Walk to the orange CPR station.
	•	When the “Press E” prompt appears, press E repeatedly.
	•	After 5 compressions, the objective will update.

Step 3 — Check the Pulse
	•	Move to the blue Pulse Check station.
	•	Press E to perform a pulse assessment.
	•	The patient status will update to “Shock advised.”

Step 4 — Deliver a Shock
	•	Walk to the red Shock Station.
	•	Press E to deliver the shock and stabilize the patient.
	•	You win once all three objectives are completed.

## Data Description (optional)

### Data Source
This prototype does not use any external datasets.
All station positions, player movement, and patient states are hard-coded in game.js.
.
├── index.html        # Main game page, UI layout, canvas element
├── style.css         # Game visuals, styling, colors, layout
├── game.js           # Core game logic: movement, interactions, objectives
├── README.md         # Project documentation
└── assets/           # (optional) Folder for future sprites, audio, etc.

Key Features:
	•	Pure JavaScript 2D game loop (no frameworks required).
	•	Simple top-down movement and interaction system.
	•	Three gameplay tasks mirroring real CPR sequence.
	•	Easily extendable to multiplayer using Socket.io later.



## Project Structure

[Description of the project structure and organization]

