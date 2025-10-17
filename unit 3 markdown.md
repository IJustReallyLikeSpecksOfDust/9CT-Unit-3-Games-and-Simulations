## =--=--=--=--=--=--=--=
## Identifying a Need
## =--=--=--=--=--=--=--=
I am going to make an adventure game with platformer mechanics.

#### **Need:**
The game will exist to provide entertainment, primarily. It will improve problem solving, precise inputs and hand-eye coordination in players.

#### **Problem Statement:**
The game does not exist to solve a problem, but instead to hopefully provide some entertainment and possibly intrigue in the vague narrative presented. But, of course, anybody can benefit from something like this to improve their skills in control over a player character, which does involve reaction time, precision, and other such things which can and do apply to real life.

#### **Skill Development:**
The primary skill I would need to develop is some, likely basic, knowledge of C# in order to program for the game to have the features I desire. For this, I have already found a collection of rescources to accomplish this, including:
##### [Microsoft's official tutorials](https://dotnet.microsoft.com/en-us/learn/csharp)
##### [The wealth of knowledge found on Youtube, like this](https://dotnet.microsoft.com/en-us/learn/csharp)
##### [Unity's official tutorials](https://learn.unity.com/)
##### [Google](google.com)

## =--=--=--=--=--=--=--=
## Requirements Outline
## =--=--=--=--=--=--=--=


### Inputs

## Controls:
Keyboard & Mouse

User inputs will be relegated to only the keyboard and mouse, as there will be limited controls. Directional keys will be used for movement, spacebar for interacting, and other keys may coincide with other features that later come into existance.


### Processing
The program checks every frame for collisions, which can happen due to input, which make up the fundamentals of the game's process. When the program detects a collision it will have different effects based on what it is intended to do.


### Outputs
If certain conditions are met, the game will have a variety of outputs as simple as seeing the character move, but also when the player dies, collects an item/upgrade, or interacts with something in the world, different reactions can occur, such as death taking the player back to a checkpoint, them gaining an ability, or dialogue appearing.


### Transmission

There will be no multiplayer or server-based aspects of the game. It will be entirely local to the player's computer.


### Storage
Selected user settings will be stored on the player's computer. The game will include a save system of some kind, and player progression data from that will be stored.


## =--=--=--=--=--=--=--=
## Requirements Outline
## =--=--=--=--=--=--=--=

### Core Gameplay Mechanics
- #### Basic Movement
The player character will be able to move around and jump, as well as look down. When the player hits one of the directional keys, the system will take that to the coinciding action (left and right walks, up for jumping, down for moving the camera). Later in the game, the player __might__ unlock more movements, such as a dash or a double jump.

- #### Interaction and Puzzles
The player will be able to interact with certain objects, characters, and puzzles in the world. This will be the spacebar, and when pressed it will check if the players hitbox is touching something designated interactable, and will provide the interaction as necessary. There will be some basic puzzles in the game that use interaction to do things like flip a lever or turn on a light.