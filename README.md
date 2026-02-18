# Mega-Connection-Game
Mega Connection 4 Word Selection Game

Mega Connections: Midnight Edition
A sophisticated, cyberpunk-themed logic puzzle game inspired by the popular "Connections" format. This edition features a sleek "Midnight" interface, dynamic category generation, and a reactive sound system.

🎮 Gameplay Overview
Players are presented with a grid of 16 words. The objective is to identify four groups of four words that share a common thread.

Four Difficulty Tiers: Every puzzle is balanced with one category from each level:

🟡 Yellow: Straightforward definitions and synonyms.

🟢 Green: Common themes and collective nouns.

🔵 Blue: Specific trivia or specialized knowledge.

🟣 Purple: Tricky wordplay, homophones, or "fill-in-the-blank" categories.

Mistakes Allowed: Players have 4 "Mistakes" (lives) per session.

Interactive Feedback: The game provides "One away!" hints when a guess is 75% correct.

✨ Technical Features
1. Adaptive Logic Engine
Unlike static puzzles, this version uses a Winnability Engine. It selects four distinct categories from a massive pool before shuffling them into the grid, ensuring every game generated is mathematically solvable.

2. Midnight Cyberpunk UI
Contrast-Optimized Color Palette: Utilizes "Midnight Overlay" text logic. Instead of harsh white-on-black, solved tiles use dark-on-color text for maximum legibility and a premium feel.

Responsive Grid: Automatically adjusts from a 4-column layout (Desktop) to a 2-column layout (Mobile) for optimal touch-screen play.

Ghost-Style Controls: Neon-bordered buttons with hover-fill transitions.

3. Audio Integration
A custom Web Audio API synthesizer generates retro-wave tones for game actions:

Selection: High-frequency blip.

Deselection: Low-frequency blip.

Success: Arpeggiated major chord.

Failure: Low-frequency sawtooth buzz.

🛠️ Built With
HTML5 & CSS3: Featuring CSS Custom Properties (:root) and Flexbox/Grid layouts.

Vanilla JavaScript: Lightweight state management with no external dependencies.

Web Audio API: Real-time synthesized sound effects.

🚀 How to Play
Open the index.html file in any modern web browser.

Click "Initialize Game" to unlock the audio and load the first puzzle.

Select 4 words and click "Submit Guess".

If you find all groups or lose your lives, click "Generate New Puzzle" to play a completely different set!
