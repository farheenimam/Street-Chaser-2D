Street Chase 2D
A colorful 2D chase game for children 5+, made with Google AI Studio. Eight runners, one hunter, and one simple rule: stand on the safe color.

About the game
Street Chase 2D is a 1 hunter vs 8 runners survival chase played in the browser.

For 10 seconds the whole map is black and white. Runners scatter and keep away from Hunter Vance.
Then the colors reveal and a Safe Color is shown at the top of the screen. It shifts every 10 seconds.
Stand on a tile that matches the Safe Color and Hunter Vance cannot chase you until the next color.
If the hunter catches you, the run ends. Your round, score and survival time are shown, and you can jump straight back in.
You can play as a Runner (pick 1 of 8) or as the Hunter and try to catch all 8 runners.

Target audience
Children aged 5 and above.

The game is built around one idea (match the color), uses big, bright tiles and a simple HUD, and needs very little reading. Families and parents who want a fun, quick game for young kids are the secondary audience.

Problem statement
Many games for young children are either too simple to hold their attention, or too complex for them, with long text, crowded screens and complicated controls. Kids who are just starting to read and play need something they can understand in seconds, but that still feels exciting and gives them a real challenge.

Solution
Street Chase 2D turns one easy rule, find the safe color, into a fast and exciting chase.

Instantly understandable: the map flips from grey to colorful, and the Safe Color is always shown at the top.
Gentle challenge: a hunter is chasing you, the safe color keeps changing, and you manage stamina for sprinting and dashing.
Plenty to explore: 8 runners with their own styles, 4 maps and 3 difficulty levels.
Kid-friendly options: tile color letters, voices, in-game rules and a pause button.
No install: it runs in the browser.
Why we made this
We wanted to make something creative, 2D, interactive, fun and challenging.

We also wanted to explore a different side of Google AI Studio. Instead of building another app, we used it to create a game, to see how far a playful and interactive idea could go.

How to play
Action	Control
Move	WASD, Arrow keys or Mouse
Sprint	Shift (uses stamina)
Dash	Space
Hide	E
Pause	P
Tip: watch the countdown at the top. When it hits zero the colors reveal, so be ready to run to the Safe Color.

Features
1 hunter (Hunter Vance) vs 8 runners
Play as a Runner or as the Hunter
8 runners: Maya, Leo, Zara, Noah, Chloe, Sam, Ava and Kai
4 maps: Whispering Woods, Metro Streets, Oakridge Campus and Harbor Plaza
Easy, Normal and Hard difficulty
Live HUD with round, runners left, score, Safe Color timer, hunter distance and stamina
Minimap
Tile color letters, voices, rules and pause options
Game Over summary with Play Again and Main Menu
Tech stack
Vite
TypeScript
HTML
Built with Google AI Studio
Getting started
You need Node.js installed.

# 1. Clone the repository
git clone https://github.com/Humaira123-afk/Street-Chaser-2D.git
cd Street-Chaser-2D

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev
Then open the local address shown in your terminal.

If the project needs environment variables, copy .env.example to .env.local and fill in the values.

Project structure
Street-Chaser-2D/
├── public/assets/aistudio/   # Static assets
├── src/                      # Game source code
├── index.html                # App entry point
├── metadata.json
├── package.json
├── tsconfig.json
├── vite.config.ts
└── .env.example
Credits
Made by Humaira and team for a hackathon, using Google AI Studio.
