# Functioning-prototype---yixu0759
### Instructions on how to interact with the work
In this game I designed, the player can press many keys on the keyboard to interact with the game:
- Up arrow keys: Move the whole field up the Z-axis
- Down arrow keys: Move the whole scene down
- Left arrow key: Moves the entire scene to the left
- Right arrow key: Moves the entire scene to the right
- "r" key: Rotate the entire scene 90 degrees clockwise along the Z axis
- "s" key: Random small cubes create a smooth bouncing animation in the Z-axis direction, while stationary large cubes remain stationary.
- "w" key: Stationary large cubes produce a smooth bouncing animation in the Z-axis direction, while random small cubes remain stationary.
- "a" key: All cubes will produce a smooth bouncing animation
- "d" key: Randomly change the color of the cube
  
### Details of your individual approach
1. The method I choose
  - User Input:Incorporate mouse or keyboard inputs for animation.

2. The properties that have been animated
  - Motion animation of Plate position
The position of the plane object can be translated based on key input. In this animation, when you press the up, down, left and right arrow keys, the plane moves along a certain axis.
  - Bounce animation of Random Boxes
When the W,A, and S keys are pressed separately, the blocks will have different animation effects in the vertical direction, they will move up and down the Z axis, and they will smoothly bounce up and down through the lerp() function.
  - Rotating animation of the scene
The entire scene rotates 90 degrees when the user presses the R key. The rotation is done by rotateScene method, and I use lerp() function to make the rotation process smooth, rather than abruptly jump to a new direction.
  - Color change animation
Color gradient: Through the toggleColorChange function, the color of the plane and the square changes randomly.

3. References of inspiration for code

  - About the way it moves![An image of a lemon]([https://placekitten.com/200/300Links to an external site.](https://dribbble.com/shots/6867072-Animated-lemon-driving-on-a-skateboard?utm_source=pinterest&utm_campaign=pinterest_shot&utm_content=Animated+lemon+driving+on+a+skateboard.&utm_medium=Social_Share)
It's "Animated lemon driving on a skateboard." I took inspiration from the way the lemons slide, adding a slow motion to the overall movement.

  - About the way it bounce up and down![An image of a ball](https://dribbble.com/shots/14140510-Loading?utm_source=pinterest&utm_campaign=pinterest_shot&utm_content=Loading&utm_medium=Social_Share)
This is a gif about loading. I got inspiration from this gif and changed the normal sliding up and down into a simple bouncing animation effect.
