# Knight: A 2D Side-Scrolling RPG Game

## Introduction
**Knight** is a 2D side-scrolling role-playing game developed using the Unity engine. In this game, players take on the role of a *Dark Knight*, exploring a world filled with enemies, obstacles, and collectible apples. By skillfully utilizing available abilities, players must defeat enemies, overcome challenges, and reach the final goal.

## Game Features
### 1. Characters and Animations
- **Player Character**: The *Dark Knight* is capable of walking, jumping (up to double jump), attacking, dashing, and taking damage. The controls include:
  - `A/D`: Move left/right
  - `Space`: Jump
  - `J`: Attack
  - `Shift`: Dash
- **Enemies**: Each enemy features basic animations such as attacking, idling, and dying. They provide a dynamic challenge for the player.

### 2. Levels
- **Tutorial**: The game starts with a tutorial area where players can familiarize themselves with the gameplay mechanics and items.
- **Main Stages**:
  - **Dungeon**: Collect apples and return.
  - **Boss Battle**: Fight and defeat a boss to obtain a golden apple.
  - **Parkour Challenge**: Traverse a parkour stage to reach various endpoints. Collecting all nine apples unlocks a secret easter egg level.

### 3. Audio
- Background music and sound effects for actions such as attacking, jumping, and taking damage were included. These sounds were inspired by *Hollow Knight* and enhance the immersion.

### 4. Tools Used
- Unity: For the primary development of the 2D game.
- Visual Studio: For writing C# scripts.

## Implementation Process
### 1. Asset Preparation
Free resources were downloaded from the Unity Asset Store, and additional *Hollow Knight* art assets were collected online for integration into the game.

### 2. Core Systems
The game development involved building several systems:
- **Combat System**: Implemented using colliders and triggers.
  - The player's sword has a hitbox. When it intersects with an enemy's collider, the attack is deemed successful, and the enemy flashes to indicate damage.
  - Damage to the player is determined by overlapping the player's collider with enemies or traps, triggering a hit animation.
- **Animation System**: Created using Unity's Animator state machine. Different states like idle, attack, or damage were managed with parameter-based transitions.
- **Audio System**: Integrated using Unity's Audio Source component. Audio effects were tied to specific events, such as attacking or jumping, through scripting.
- **AI System**: Implemented basic enemy AI for chasing the player, and a boss with collision-based damage.

### 3. Levels and UI
- Designed three main levels and an introductory tutorial scene.
- The UI includes health and collectible counters to track the player’s progress.

## Highlights and Unique Features
1. **Double Jump**: Allows precise movement with a restriction to only two jumps per airborne session.
2. **Dash with Invincibility Frames**: Adds dynamic movement while temporarily granting immunity.
3. **Hit Feedback**: The player recoils and gains temporary invincibility upon taking damage, while enemies flash when hit.
4. **Nonlinear Gameplay**: Multiple paths and endings are available, encouraging exploration and replayability.
5. **Easter Egg Scene**: Unlockable by collecting all apples.

## Reflection
Creating *Knight* was an enriching experience that combined creativity and technical problem-solving. From coding character movement to designing engaging levels, the development process provided invaluable learning opportunities. The project highlights the importance of modular coding, effective time management, and perseverance in overcoming challenges. Despite some limitations, such as the absence of advanced mechanics like upward or downward strikes, the game showcases a solid foundation for further improvement.

Through this project, I gained a deeper understanding of Unity and game development principles, setting the stage for more ambitious projects in the future.

---
