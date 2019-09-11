UNHEARD

Designed and Developed by Ajayi Joy
Version 1.0
Created 24.08.2019
Last modified 10.09.2019
PROGRESS REPORT
Date	Changes
24.08.2019	Started the GDD and began to bring idea to life.
26.08.2019	Created and designed the UI pages
27.08.2019	Finalized the designs of the UI pages and attached the necessary blueprints node 
28.08.2019	Designed Level 2 and its HUD
31.08.2019	Designed Level 1 and its blueprint
2.09.2019	Solved the movement problem of the panels in level 1. 
Implemented main menu and start menu
5.09.2019	Implemented Level 1 character and character movement. 
Also Level 1  HUD
6.09.2019	Animated the stones in Level 2. 
Implemented Enemy for level 2
9.09.2019	Time count, target count functionality enabled.
Health progress bar fixed. 
Blueprint of Enemy scripted. 
Level 2 game mode converted to FPS.
11.09.2019	Implemented coin
Paused Menu designed and implemented
Built and packaged it

1 OVERVIEW
1.1	High Concept Statement
Unheard is a 3D single player game for PC, where the player undergo series of tests to determine his eligibility for knighthood.
1.2	Gameplay
Unheard is a single player game, with a follow camera attached to the character, where the player compete against various obstacles to win.
Player’s objective is to get certain medals across levels and complete the belt of victory.
In the first level, the player is to search for the member medallion in a maze and prevent itself from running into foreign objects which depletes his life. Once, the member medallion is retrieved the player wins and can move to the next level.
In the second level, the player has to eliminate a certain number of targets that are hidden in the world (and only appear at random). This level is timed and the targets must be eliminated in sixty seconds. The level is won once the goal is met and a dame medallion is awarded.
In the final level, the player is not visible but has to solve a puzzle in a certain number of moves before the knight medallion is awarded.
 

1.3	Game World
The game has two levels varying in size and designed using basic geometry shapes. 
The textures and materials used to further design were made available by Unreal Engine Starter content.
Music and sound effects are also products of the starter content
1.4	Genre
The game has no specific genre.
1.5	Platform and Licenses
Windows PC’S with keyboard control system
Game will be created with the Unreal Engine 4 (4. 22) game engine.
1.6	Target Audience
Unheard is targeted at recruiters. It shows the basic understanding of application of blueprints in Unreal Engine and ability to manipulate them.
1.7	Competition
Unheard does not have any direct competition because there is no game like it in existence. Even when shipped it will be a conundrum has it follows no  game design pattern established.
1.8	Unique Selling Points
It is a non-profit game.



2	GAMEPLAY AND MECHANICS
2.1	Camera
The game’s view will be from top-down perspective angle, in a way that the ground is in perspective but everything else is facing the camera.
The camera follows the player so that the player is always in the center of the screen.
2.2	Controls
                    
P for pausing the game.
2.3	Movement
Player moves on Z(Yaw) plane. A forward, left, right and backwards.


3	CHARACTERS
3.1	Appearance
The Skeletal Mesh is the default mannequin provided by Unreal. Character color is silver and it’s enemies a rusty color.
3.2	Animations
Movement – Character  can walk and jump.
Contact – Health of the character depletes on contact with enemy.


4	GAME WORLD
4.1	Art
Level 1 is a wooden maze with moving panels which reduce the health of the player on contact with it.
 
Level 2 is a stony landmass with rolling stones and enemies scattered across the level.
  


4.2	Sound
It is a quiet games. Sound is only available when the player is approaching the enemy and is about to shoot.


5	USER INTERFACE 
5.1	Menus


 5.2	HUD
TIME is visible at the centre of the screen in level 2. 
NUMBER OF MOVES is visible at the centre of the screen in level 3.
PLAYER’S HEALTH is visible at the centre of the screen in level 1. The health bar is green in color and it is reduced on collision with moving objects
