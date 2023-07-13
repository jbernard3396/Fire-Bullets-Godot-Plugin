# Fire-Bullets-Godot-Plugin
Plugin for godot that allows you to quickly add shooting to your game

This tool will allow you to quickly make a node shoot a bullet(s).

with:
  Gun node:
    
    number of bullets to be fired
    cooldown(cooldown before firing again)
    angle variance(for accurate/inaccurate shots)
    customizable shooting arc(like in shotguns)
    customizable spawn point
    debugs! - for spawnpoint and shoot_arc
  Bullet node:
    
    delete after( time to delete the bullet node after shooting )
  
  + Documentation  on all methods!

setup:

    install the addon in the assetlib or in the github(code -> download zip)
    then put that in your addons/ folder in you godot project:)

How to use:

    1.create a new scene and add bullet node and save it as a scene.
    2.in another scene, add the gun node and put your bullet scene in the "bullet" paramater in the inspector. 
    3.then set the other paramters of the gun node to your fit your game.
    4.you can fire the gun by calling Gun.shoot(speed,angle)

thats all! more description in the documentation!
