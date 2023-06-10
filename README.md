# Minecraft Floor is Lava

## Description
Minecraft Floor is Lava is our project that takes heavy inspiration from the childhood game "The Floor is Lava." You play as a burger jumping from one platform to another collecting coins. Once you have collected all of the coins for that level, an arrow spawns showing the final platform you must jump onto to proceed to the next level. If the user misses a jump and lands in the lava, they "die" and have to restart. If the user "dies" 3 times, the level is reset and 
they lose all of their coins.

<p align="center">
    <img width="241" alt="Screenshot 2023-06-09 at 10 36 23 PM" src="https://github.com/Nate-Fish/dummy/assets/77850450/95132c3a-7a3b-4fd6-904e-84f48b52d9da">
</p>
## Features and Topics from the course
- Transformations
    - We used transformations by translating and rotating the players position and other objects around world space.
- Vectors/Matrices
    -  We use vectors/matrices (specifically, cross products) to determine which direction a player should move when clicking A, W, S, and D.
- Camera/Eye space
    - We use camera/eye space to have a 1st and 3rd person perspective.
- Particle Rendering
    - The lava floor has particles bubbling up from it to make it look like lava. 
- Lighting and Texturing
    - We used lighting and texturing to make the program more visually appealing. More specifically, you can see how we decided to texture the platforms (which are modeled as pillows) and you can see how we textured our character (who is a hamburger). In addition you will notice lighting in our environment. When you look at the rings that you collect, there are specular highlights.

## Advanced Features
Although we are a two-person group we decided to implement an advanced feature: collision detection. The character is able to jump from pillow to pillow and does not phase through. This was a critical component of getting our game to work.


## Setup
To start the game, run 
```./host.command``` or ```python3 server.py```
 in the terminal on a computer with python installed. This will start a webserver at
```localhost:8000``` where you can navigate to to find the game.

### Interactivity/Controls
- To move around the world, use the WASD keys to move in forward, left, down and right respectively.
- To jump, press the space bar
- To look around, use the mouse (or i and o to zoom in and out if in third-person POV)
- Press c to swap between first and third-person POV
