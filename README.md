![UnrealEngine](https://img.shields.io/badge/Unreal%20Engine-Learning-red)
# Unreal Engine 4 Archero Recreation
# Link to the gameplay video: 


[![Archero Recreation Unreal Engine](https://img.youtube.com/vi/h3HG1Fals78/0.jpg)](https://youtu.be/h3HG1Fals78)

https://youtu.be/h3HG1Fals78

## Game Description
This game is a recreation of the Archero Mobile game. You can move the main character with WASD. If you release WASD and the character approaches an enemy, he will automatically aim and shoot him. If you kill an enemy you will gain 10 pickups. Your character will level up every 100 points.


## CUSTOM BLUEPRINTS:
- Custom camera movement: Camera only moving when player go upwards or downwards.

<img src="https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/CustomCameraMovement.JPG" title="Particles">

## PARTICLE EFFECTS:
 Ghost single particle used in the enemy death effect:
 

<img src="https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Particle1.JPG" width="400" title="Particles">

 
 Step dust particle: This particle will spawn every 2 character's steps.
 

 <img src="https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Particle2.JPG" width="400" title="Particles">
  
## HUD and 3D UI:

- Current Character's level:
 <img src="https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/HUD2.JPG" width="400" title="Particles">

- Current Character's health:
 <img src="https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/HUD.JPG" width="400" title="Particles">


## SOUNDS:
 
 - 3 sound queues: Enemy sounds, step sounds and character sounds.
 
 ![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Sounds1.JPG)
 
 ![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Sounds2.JPG)
 
  ![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Sounds3.JPG)
 
 - Step sounds placed in animation:
 
  ![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/SoundsSteps.JPG)
 
  ## TERRAIN:
  - We didn't have any terrain in game, but we've worked to create a 2D terrain with tilemaps and tilesets
  
![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/TileMap2.JPG)

  ## PHYSICS:
  - Projectiles: This blueprint uses physics collisions and gravity. This element only can interact with floor and character.
  
![Physics]( https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Projectiles.gif)
 
  - Pickups: Physics are deactivated when each element touches the ground so that the player can attract them.

![Physics](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Physics.gif)
 
 ## BONUS POINTS:
  - Persistent data: We store the current character level and health.
  
Game Instance:
![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/PersistentData_GI.JPG)

Loading player state:
![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/PersistentData_LoadPlayerState.JPG)
![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/PersistentData_LoadPlayerState_Init.JPG)

  
  - 3 different enemies: 
  
  <img src="https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/Enemies.png" title="Particles">

  
  - Character Custom animation:
  
![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/CharacterAnimation.JPG)
  - Custom weapons placed in character:
  
![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/CharacterWeapon.JPG)
   
  - HUD animation for transitions between levels:
  
  ![Color]( https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/transition.gif)
  
  
  - Character Retargetting:
  
  - Artificial Intelligence:
  
  - Loading levels in game runtime:
![Color](https://github.com/incodemon/Archero-recreation-in-UnrealEngine/blob/master/data/LoadLevelBP.JPG)

  - 2D Sprites and Tilemap
  
## STYLE AND ARTWORK
  - We've used the modular Sci-Fi Kitbash Level Builder: https://www.unrealengine.com/marketplace/en-US/product/scifi-kitbash-level-builder
  - We've used the original Doom's sound FX, GDC 2018 & 2019 audio packs and some Infinity Blade Effects (https://www.youtube.com/watch?v=VMbPHuU1KRs)
  - Player can be controlled with keyboard and mouse and we added the controller input.
  - We've tryed to mimic some Doom saga tipical mechanics (Shooting targets and enemies, gates, canons, keys...)
  - Research we've made: UI, Sounds, AI, animation (the NPC is made with a custom animation), triger area.
