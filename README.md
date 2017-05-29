# Valley of The Living Dead

![binus_university_international](http://international.binus.ac.id/wp-content/themes/binus-2014-58-core/assets/university/site-logo/international/site-logo-lg.png)

Revision: 0.0.0

Final Project Report  
Game Design Development

Group 4

Ferlix Yanto Wang / 1901498435  
Kensen / 1901504785  
Michael Fernanlie / 1901530133


COMP6205 – Computer Graphics  
Computer Science Program  
Bina Nusantara University International  
2016/2017




## Contents

* ### [Overview](#Overview)
	* [Genre](#Genre)
	* [Project Description](#Project-Description)
	* [Core Gameplay Mechanics Brief](#Core-Gameplay-Mechanics-Brief)
	* [Targeted Platforms](#Targeted-Platforms)
	* [Project Scope](#Project-Scope)
	* [Project Limitation](#Project-Limitation)

* ### [Story and Gameplay](#Story-and-Gameplay)
	* [Story](#Story)
	* [Gameplay](#Gameplay)

* ### [Assets Needed](#Assets-Needed)
	* [2D](#2D)
	* [3D](#3D)
	* [Animation](#Animation)

* ### [Schedule](#Schedule)
	* [Week #1](#Week-#1)
	* [Week #2](#Week-#2)
	* [Week #3](#Week-#3)
	* [Week #4](#Week-#4)
	* [Week #5](#Week-#5)

* ### [Screenshot](#Screenshot)





## Overview


### Genre
* Action
* Survival
* Third-Person Shooter


### Project Description
>This game is part of the final project of the Computer Graphics course. The title of the game is Valley of The Living Dead. It is an action-survival third-person shooter game. The setting of the game takes place in a mountain range. The objective of the game is for Jimmy, the protagonist, to protect his family from zombie menace approaching. It took around 5 weeks to finish the project.  
  
>In this game, the player is initially placed in front the house which is going to be approached by a horde of zombies. The main character can move freely in all direction. The player can shoot the zombies to kill them and reload the weapon when the gun is out of ammo. For each zombie kill, the player receive score points. The player must protect the house as long as possible from the attack to get the highest score.  

>The game is easy to play, but hard to master. These are the steps of how to play the game:
1.	When the game starts, click on the `Start Game!` button to start playing.
2.	Then, click on the middle of the crosshair as instructed by the game.
3.	Use `WASD` button to move the character around.
4.	Slide the mouse around to move the camera.
5.	Use `C` button to pause the game.
6.	Use `Left Mouse Button` to shoot.
7.	There are 10 bullets for each magazine clip of the gun. When the gun ran out of ammo, an ammo crate will be spawned. Retrieve to reload.
8.	The enemies will be spawned randomly and comes from four general direction of the house. So, make sure to cover the four side of the house.
9.	Don’t let the enemies reach the house, they will reduce the health bar. The house can only withstand 5 attacks.

>In the making of this game, several models are needed to make the game realistic. The game has 2 character models. The first one is the main character, he can walk, shoot, and reload. The second is the zombies, they can walk to their objective. The game also has 3 environmental models. They are the house, the ammo crate, and the mountain range.


### Core Gameplay Mechanics Brief
* #### Protect A Target
	The player must protect a target from enemies that move towards it.

* #### Movement
	The player can move forward and backward, strafe right and left, and move diagonally.

* #### Shooting
	The player consumes a bullet every time the player shoots. When the player run out of bullets, an ammo crate will be spawned.

* #### Scoring System
	For each enemy the player kills, the player receive score points.


### Targeted Platforms
The game runs on Web Based Platform, but it is limited to several web browsers such as Google Chrome and Mozilla Firefox due to the incapability of other browsers to load the object and run the engine of this game.

### Project Scope
* Game Time Scale  
The estimated time to finish this project is around 5 weeks and the milestones of each week will be discussed further on another section (see section [Schedule](#Schedule)).

* Team
The team consists of 3 members, they are:
	1. Ferlix Yanto Wang  
		Student ID: 1901498435  
		Github Account: ferlixwangg  
		Task Performed:
		* Preparing the terrain
		* Implementing the objects and algorithms into the project
		* Creating action manager for the objects
		* Creating enemies' spawn points
		* Creating ammo boxes' spawn points

	2. Kensen  
		Student ID: 1901504785  
		Github Account: kensentjoa  
		Task Performed:
		* Creating a third-person shooter camera 
		* Creating the algorithm for character movement
		* Creating the algorithm for shooting
		* Creating the key binding mechanism
		* Applying crosshair

	3. Michael Fernanlie  
		Student ID: 1901530133  
		Github Account: mfernanlie  
		Task Performed:
		* Determining appropriate models to be used 
		* Character rigging
		* Creating user interface
		* Create and maintain the quality of soundtrack used in the game
		* Applying scoring system

* Licenses / Hardware  
	Credits:  
	* Project Report Template by Alec Markarian and Benjamin Stanley
	* Soundtrack “A Fistful of Dollars” composed by Ennio Morricone
	* [Army Object](https://free3d.com/3d-model/army-pilot-fully-rigged-animated-20-animations-57044.html) by nathandavis
	* [House Object](https://free3d.com/3d-model/old-farm-house-91130.html) by animatedheaven
	* [Zombie Object](https://free3d.com/3d-model/zombie-man-86116.html) by steve45

* List of Tech / Library Being Used
	* Babylon.js
	* Castor GUI
	* Hand.js
	* [Timer.js](https://free3d.com/3d-model/old-farm-house-91130.html) by Temechon



### Project Limitation

* #### Collision
	Collision was failed to be applied to our final project. Meaning that when two objects intersect and one of them isn’t a collectible, both these objects would go through each other, as opposed to be halt its movement due to collision. Consequently, if the player were to walk into stationary object such as house and mountains, they would go through these objects as if they weren’t there.

* #### Zombie / Enemy Animation
	Due to an unknown error, spawned zombies may not have a properly working animation on several occasion. When such occasion arise, some zombie may be moving towards the house without any walking animation, making them as if they are being moved by a string.

* #### Unpolished Models
	Some models like player and zombie models are unpolished. This might be observable through unintentional hole on the zombie’s neck. 

* #### Goalless Gameplay
	Aside from getting the highest score in the game, objectives that are considered to be worth achieving might seems lacking in this game for the player. This could affects player’s will and responsibility in protecting the house from the zombies, and the elements of the gameplay might at times seems repetitive.



## Story and Gameplay

### Story
&ensp;&ensp;&ensp;Jimmy, a US Army who had just finished his 10 years military services at US war post over at Russia. Relieved of his duty, Jimmy returned to his homeland America to embrace his loved ones. But, he was in agonizing shock when he found out no love was waiting for him. What awaits him however, is a scene of horror that no sane man could ever describe. Plague has infected his country and driven its people insane. People he once knew, was no more than rotten flesh now. With bits of hope and sanity left in Jimmy’s mind, he hurried to his home to clarify the safety of his family. And away he went, safety of his family was assured. But Jimmy feared the safety wouldn’t last long, as he gazed as far as his eye can see to picture the dead man walking to them as if they were alive. Well supplied with his experience in combat, Jimmy ventured forth with his trust-worthy gun to protect what he cared for the most.

### Gameplay
&ensp;&ensp;&ensp;In this game, the player must protect his/her house from zombie attacks. The attack comes from 4 different directions and for that the player must keep moving to secure the house. To eliminate the threat, the player can shoot the zombies with a rifle. The rifle magazine clip only holds 10 bullets and each time the player shoots, the bullet count decreased. Once the player runs out of ammo, an ammo crate will be spawned near the house and the player must retrieve the crate in order to reload and continue shooting the zombies.



## Assets Needed

* ### 2D
	Textures
	* Sky Texture
	* Grassland Texture
	* Mountain Texture
	* House Texture
	* Army Texture
	* Zombie Texture
	* Ammunition Texture

* ### 3D
	* Characters List
		* Army (Player)
		* Zombie
	* Environmental Arts List

* ### Animation
	Character Animations
	* Player
		* Reloading
		* Shooting
		* Walking
	* Enemy Walking




## Schedule

* ### Week #1
	* Decide our game (final)
	* Start looking for model to be used

* ### Week #2
	* Making movement with WASD (most polished version)
	* Applying animation to models
	* Started making terrain for our game environment

* ### Week #3
	* Implemented crosshair by means of third person camera
	* Researched on path-finding algorithm for game’s enemies
	* Started looking for sound effects, bgm, and other creative contents

* ### Week #4
	* Started spawning enemies and collectibles
	* Made main menu and other user GUI (health bar, bullets, and scoring screen)
	* Crosshair can now follow cursor and pick in-scene objects

* ### Week #5
	* Assembling our separated works
	* Refining and polishing the completed program with a bit of creative contents



## Screenshot

![main menu](http://i.imgur.com/Zz1PoVc.png)

![click to start](http://i.imgur.com/mLtSMIf.png)

![gameplay](http://i.imgur.com/Dyx4dfr.png)

![ammo crate](http://i.imgur.com/2nRSSbQ.png)

![zombie hit](http://i.imgur.com/14Y3iF0.png)

![pause](http://i.imgur.com/DjRQ4P8.png)

![game over](http://i.imgur.com/tgiNDPS.png)