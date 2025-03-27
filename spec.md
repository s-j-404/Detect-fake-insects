Game Objective:
In this engaging visual challenge, players must distinguish between real insect photographs and AI-generated images. The goal is to identify the synthetic insect in a pair of pictures presented each round.

Image Resources:
The game utilizes two distinct image sets located in the /insects directory:
1. /r: Contains 100 authentic insect photographs (numbered 01.png to 100.png)
2. /f: Contains 100 AI-generated insect images (numbered 01.png to 100.png)

Preloading for Smooth User Experience:
To ensure a seamless gameplay experience, a subset of images from both the real and synthetic collections is preloaded at the start of the game. This preloading mechanism helps minimize load times between rounds, resulting in smoother transitions and more fluid gameplay.

Gameplay Mechanics:
1. Round Setup:
   - The game randomly selects one real and one synthetic insect image from the preloaded set that haven't been used in previous rounds.
   - These two images are displayed side-by-side for the player to examine.

2. Player Interaction:
   - The player must click on the image they believe to be AI-generated.
   - Correct identification (clicking the synthetic image) awards one point and advances the game to the next round.
   - Incorrect selection (clicking the real image) immediately ends the game.

3. Time Constraint:
   - Each round has a 25-second time limit.
   - The remaining time is visually displayed and decrements each second.

4. Scoring:
   - Players accumulate one point for each correctly identified synthetic insect.
   - The game concludes upon a single incorrect selection.
   - Upon game over, the player's total score (number of correct identifications) is displayed.

This specification now includes the preloading feature, which enhances the end-user experience by reducing wait times between rounds and ensuring smooth gameplay progression.