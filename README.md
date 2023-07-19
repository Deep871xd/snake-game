# snake-game
It is a Java project that uses the inheritence, abstraction, and encapsulation concepts found in object-oriented programming. All the parts are organised using the JAVA Swing and AWT library.

# It icludes two main classes:

Snake (extends JFrame and invokes the GameControl class) GameControl (extends JPanel)

# The GameControl class provides following methods:

**GameControl()** - It initializes Board Panel. 
**loadImages()**- It loads images of Snake head, Snake body and food. 
**initGame()**- It initializes Game. 
**checkCollision()** - It checks collision of Snake's head with an obstacle (itself/food/wall). 
**locateApple()** - It randomize Apple position every time. 
**gameOver()**-It displays Game Over massage and player's score.

# This game includes the following functionalities:

The player can move the snake left, rigt, up, and down as per the given direction using respective arrow keys. Whenever the snake eats food, its length increases by one and live score is displayed on screen. The food appears on random position each time, either when the snake eats one or the new game is started. When the snake collides with itself or with any of the wall, the "Game Over" massage it displayed along with player's score.

# Design elements -

**Snake head:** represented by green dot. Snake body: represented by red dot. Food: represented by an apple.

![36a8b1fc-ce95-426c-ad7b-2759ae324d9d](https://github.com/Deep871xd/snake-game/assets/102525444/f32ab354-6db0-4fff-a0ba-017ce69f563d)

![9d0a9201-590f-4249-8c23-fec792e29336](https://github.com/Deep871xd/snake-game/assets/102525444/0659ab24-a8b6-421a-a28d-63144039bc63)

