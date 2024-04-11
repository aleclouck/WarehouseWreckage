<br/>
<p align="center">
  <h3 align="center">Wrecking Crew
</h3>

  <p align="center">
    My First Unreal Engine 5 Game Project!
    <br/>
    <br/>
  </p>
</p>


![Screen Shot](Screenshots/WreckingCrewProfileScreenshot.PNG)


## Built With

Unreal Engine 5.3<br/>
Blueprint Programming<br/>
Industry Props Pack6<br/>

## Getting Started

Space bar to shoot and watch the physics do their thing!
You have 20 ammo The game will let you know when you are out and then reset the level

I have a lot of experience with Unity so this project was very fun!

## What I Learned

Blueprint Programing!<br/>
  -Nodes, IO Pins, Flows, and Connections!<br/>
  -It's very intuitive node-based programming I'm a big fan!<br/>
Unreal Basics: Maps, Actors, Children Parents (with the Rack Prop), Components, Transforms, Vectors, Building new basic Colider meshes (for the Barrels)<br/>
  -I already knew all of this from my time with Unity but it was fun to learn them in a new engine environment<br/>
BrushComponents<br/>
-I had never used anything like brush components before in Unity so this was a nice surprise feature!<br/>
I used subtractive brush components to hollow out the room and create easily moveable window holes it's a very useful tool sort of like a loony toons hole :)

## Game
![Gif](Screenshots/WreckingCrew.gif)<br/>

## Level Code
![Screen Shot](Screenshots/LevelCode.PNG)<br/>
Making functions out of blocks of nodes makes code a lot more readable while also not removing the ability to drill down and get deeper into the nuances of the programming.

## Spawn Projectile
![Screen Shot](Screenshots/SpawnProjectile.PNG)<br/>
The Spawning projectile code was maybe the hardest part aligning the projectile with the player pawn's position and view angle 

## Decreace Ammo
![Screen Shot](Screenshots/DecreaceAmmo.PNG)<br/>
Once I had an ammo variable decreasing it in the blueprint was pretty easy and instead of messing with Ui elements just yet I opted to have a simple scope for this project and simply print it on the screen once out of ammo an additional space bar press calls Restart level function.

## Print Ammo Count
![Screen Shot](Screenshots/PrintAmmoCount.PNG)<br/>
Print Ammo is pretty self-explanatory it prints your ammo count on the screen so you know how much you have.


## RestartLevel
![Screen Shot](Screenshots/RestartLevel.PNG)<br/>
Restart Level resets the level as a placeholder for a level transition.

## Launch
![Screen Shot](Screenshots/Launch.PNG)<br/>
The Launch function added an impulse to fire the projectile off along with adjusting its mass and impulse power to give the projectile the power it needed to do some destruction!

