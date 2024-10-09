## Getting Started with Flappy Bird Game

This is a game project developed on VS Code using Java, Swing(JPanel, JFrame), KeyListeners and ImageIO

### Creating the Game Window
- The window dimensions are set to 360 pixels wide and 640 pixels high, matching the background images.
- A JFrame is created for the game window, and settings like center location and non-resizable window options are configureds.
- The JPanel is utilized for the game canvas, and it inherits from the JPanel class to incorporate its functionalitiess

### Adding Images and Drawing
- Several image variables are defined to hold images of the background, bird, top pipe, and bottom pipes.
- The paintComponent method is overridden to draw the background image onto the game panel using specified dimensionss.

### Implementing Bird Movement and Physics
- Velocity is introduced to the bird, which moves upward when space is pressed, and gravity is applied to create a realistic motionss.
- A key listener is implemented to handle the bird's upward movement when the space bar is presseds.

### Adding Pipes to the Game
- Pipes are generated to the right of the screen at specific intervals, moving leftward at a velocity to simulate continuous gameplayss.
- Randomization is introduced for the vertical position of pipes, ensuring varied gameplayss.

### Game Over Conditions
- Two key conditions cause the game to end: the bird falling outside the game window or colliding with the pipesss.
- The program monitors these conditions and halts the game loop when a game-over state is detecteds.

### Scoring System
- A scoring system is implemented where players earn points for passing through pipes, adding a competitive element to the gameplayss.
- The score is displayed on-screen, showing how many sets of pipes the bird has successfully flown pasts.

### Restarting the Game
- The game can be reset by pressing the space bar after a game over; this involves resetting all relevant variables to their initial states.
- Successful implementation allows for a seamless transition from game over back to gameplays.

### Conclusion
- Successfully demonstrated the complete process of creating a Flappy Bird game in Java, integrating all essential gameplay features.
- Emphasized hands-on coding experience in game development, enhancing understanding of object-oriented programming and GUI design.
