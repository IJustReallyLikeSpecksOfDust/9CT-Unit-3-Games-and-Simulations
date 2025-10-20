### =--=--=--=--=--=--=--=
## Identifying a Need
### =--=--=--=--=--=--=--=
I am going to make an adventure game with platformer mechanics.

#### **Need:**
The game will exist to provide entertainment, primarily. It will improve problem solving, precise inputs and hand-eye coordination in players.

#### **Problem Statement:**
The game does not exist to solve a problem, but instead to hopefully provide some entertainment and possibly intrigue in the vague narrative presented. But, of course, anybody can benefit from something like this to improve their skills in control over a player character, which does involve reaction time, precision, and other such things which can and do apply to real life.

#### **Skill Development:**
The primary skill I would need to develop is some, knowledge of C# in order to program for the game to have the features I desire. For this, I have already found a collection of rescources to accomplish this, including:
##### [Microsoft's official tutorials](https://dotnet.microsoft.com/en-us/learn/csharp)
##### [The wealth of knowledge found on Youtube, like this](https://dotnet.microsoft.com/en-us/learn/csharp)
##### [Unity's official tutorials](https://learn.unity.com/)
##### [Google](google.com)

### =--=--=--=--=--=--=--=
## Requirements Outline
### =--=--=--=--=--=--=--=


## Inputs

### Controls:
Keyboard & Mouse

User inputs will be relegated to only the keyboard and mouse, as there will be limited controls. Directional keys will be used for movement, spacebar for interacting, and other keys may coincide with other features that later come into existance.


#### Processing
The program checks every frame for collisions, which can happen due to input, which make up the fundamentals of the game's process. When the program detects a collision it will have different effects based on what it is intended to do.


#### Outputs
If certain conditions are met, the game will have a variety of outputs as simple as seeing the character move, but also when the player dies, collects an item/upgrade, or interacts with something in the world, different reactions can occur, such as death taking the player back to a checkpoint, them gaining an ability, or dialogue appearing.


#### Transmission

There will be no multiplayer or server-based aspects of the game. It will be entirely local to the player's computer.


#### Storage
Selected user settings will be stored on the player's computer. The game will include a save system of some kind, and player progression data from that will be stored.


### =--=--=--=--=--=--=--=
## Functional Requirements
### =--=--=--=--=--=--=--=

### User Interaction
Most things will be done with directional keys, as well as a few others such as space or Q that may have other roles. Some menus will use mouse control. For more elaboration, see below.

### Core Gameplay Mechanics
- #### Basic Movement
The player character will be able to move around and jump, as well as look down. When the player hits one of the directional keys, the system will take that to the coinciding action (left and right walks, up for jumping, down for moving the camera). Later in the game, the player __might__ unlock more movements, such as a dash or a double jump.

- #### Interaction and Puzzles
The player will be able to interact with certain objects, characters, and puzzles in the world. This will be the spacebar, and when pressed it will check if the players hitbox is touching something designated interactable, and will provide the interaction as necessary. There will be some basic puzzles in the game that use interaction to do things like flip a lever or turn on a light.

### Scoring and Feedback
Largely inapplicable. Tips may appear on death. Or not.

### Level Progression
The game will have a wide, singular world. This may be split up into different screens, which may require challenges or upgrades to reach. The game's progression is currently planned to be partially non-linear, with players able to choose different areas to challenge themself. Advancing will require completing especially difficult challenges, possibly including survival gauntlets and _incredibly large maybe_ bosses.

### Saving and Loading Data
The game will include a save option for players to use freely. It will also include a few options, which will save when enabled or disabled. Progress will be saved into a document on the player's computer, which can be read to get it back.


### =--=--=--=--=--=--=--=
## Non-Functional Requirements
### =--=--=--=--=--=--=--=


### Performance Requirements
The game shouldn't experience any major framerate issues, should load briefly (<2s), and have zero real issues performance wise, being a relatively simple, pixelated 2d platformer. Controlling the player should be easy and feel quick, with minimal time between input and output.

### Usability Requirements
There will be most unintrusive UI in corners informing the player of their current health, and anything else major, without obscuring anything gameplay-related. The tutorial will not be based on text, but rather a small opening area where the player can easily get their barings on the controls. Interaction and any other abilities will be taught thorugh small text on screen when applicable.

### Compatibility Requirements
The game will run on windows computers, using keyboard and occasionally mouse. Players may also be able to use a controller as well. Probably not, though.

### Scalability Requirements
The game has already been scaled back, and as such has extreme scalability possibility. New areas, upgrades, features, or scenes could all be added. The scripts will be programmed to simply focus on systems rather than specific things, and so more anything can be added to those systems without too much impact. Scene transitions will likely be used to prevent any performance impact from scope creep.

### Security Requirements
The program has no reason to collect any user data, and no reason to store it. As such, there are few security requirements, the player won't even have to enter a username. Save data will be easily accessible, and if players want to modify it they can, as it is a singleplayer game.

### Reliability and Availability
No online functionality is required. Save data should always be safe so long as players choose not to tamper with it.

### =--=--=--=--=--=--=--=
## Consideration of Social Issues
### =--=--=--=--=--=--=--=