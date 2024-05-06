# What i did and why i did it?

The first mechanic that fascinated me as a child was the ability for the hero to run through a 360-degree loop. What fascinated me even more about this mechanic was that you could only achieve it by reaching a sufficient speed. There were two ways to accomplish this. The first way was to go in a straight line without bumping into enemies or obstacles. If you succeeded, the hero would increase speed and change animations, transitioning from a walk to a jog and then to a run. In my game, I also implemented speed acceleration for the player if they didn't collide with enemies, obstacles, or walls. The second way to gain enough speed to pass the loop was to accelerate using a speed-increasing panel. This panel would give the hero maximum speed and rotate them in the direction the panel was facing, just like in the original game. Only under one of these conditions could you run on a 360-degree loop. Additionally, if you stopped running or jumped, you would fall from the surface.

The second mechanic I worked on was fast collecting rings. Before I describe the workings of this mechanic, let me explain the significance of rings in the game. Rings served as the player's health. You could collect them, and if you took damage, you would lose them. If you sustained damage, you would lose 20 rings if you had that number or more. If you had fewer than 20 rings, you would lose all of them. When lost, the rings would drop from the player and form a circle. They were physics objects that would bounce off surfaces and walls. If you lost rings, you had 15 seconds to collect them before they disappeared. Before disappearing, they would blink, and if you failed to collect them, they would vanish. Now that you have an understanding of rings in the game, let me explain the mechanic. When there is a line or curved line of rings, you can fast collect them by traveling in their direction. Let me explain in more detail. When there is, for example, a line of rings and you are close to them, you can press the "X" button, and your hero will travel along that line, collecting the rings. Isn't that cool? The rings can even form a curved line to create a 360-degree loop, and the player will still travel through them. This mechanic works in both directions, just like in the original game.

The third mechanic was expanding the functionality of a dash panel (which I described in the first mechanic about the 360-degree loop). In the original game, there were not only panels that increased the player's speed but also panels that propelled the player through the air to cover large distances where there was no ground below. Similar to the original game, I implemented it in a way that the player couldn't take action while being propelled by the force of the panel.

The fourth game mechanic, although more like AI than a mechanic, has some patterns that resemble mechanics. It involves enemies that chase you when you are within their range and attack if you are in front of them. There is more to these enemies, such as their animations and attacking methods, but that will be covered in another mechanic.

Fifth, there are springs in the game that accelerate the player upward upon collision.

Sixth, Homing attack. If you asked what my second favorite mechanic is, I would definitely say that it is the homing attack. When you press the "Space" button or are in the air by spring acceleration, you can press the "Space" button to homing attack the closest enemy or the closest spring. When your hero is homing attacking, he is immune to damage. Like in the original game, when the player homing attacks an enemy, he will be accelerated up, and when he homing attacks a spring, he will be accelerated up by the spring.

Seventh, gun shooting and reloading. The hero you are controlling has a gun in his right hand that can shoot by pressing the "Z" button. When you shoot, a shoot animation will play, as well as the sound of the shoot, and a bullet will come from the gun. The bullet can collide with enemies. That action will destroy the bullet as well as the enemy. After shooting, you won't be able to shoot again for a while. You will be able to shoot again when the hero reloads the gun. You will notice that you can shoot again by the reloading sound. I understand that Sonic games are more about speed, platforming, and adventure, and in other Sonic games, that mechanic was never implemented again. I really liked another option to destroy enemies.

Eighth, even though it's not a mechanic at all, I want to mention that I added animations, sounds, andFor my final project, I created a level using the Unity engine based on my favorite childhood game, "Shadow the Hedgehog," which was on the PS2. Specifically, I focused on implementing the mechanics that I enjoyed the most as a child.

The first mechanic that fascinated me as a child was the ability for the hero to run through a 360-degree loop. What fascinated me even more about this mechanic was that you could only achieve it by reaching a sufficient speed. There were two ways to accomplish this. The first way was to go in a straight line without bumping into enemies or obstacles. If you succeeded, the hero would increase speed and change animations, transitioning from a walk to a jog and then to a run. In my game, I also implemented speed acceleration for the player if they didn't collide with enemies, obstacles, or walls. The second way to gain enough speed to pass the loop was to accelerate using a speed-increasing panel. This panel would give the hero maximum speed and rotate them in the direction the panel was facing, just like in the original game. Only under one of these conditions could you run on a 360-degree loop. Additionally, if you stopped running or jumped, you would fall from the surface.

The second mechanic I worked on was fast collecting rings. Before I describe the workings of this mechanic, let me explain the significance of rings in the game. Rings served as the player's health. You could collect them, and if you took damage, you would lose them. If you sustained damage, you would lose 20 rings if you had that number or more. If you had fewer than 20 rings, you would lose all of them. When lost, the rings would drop from the player and form a circle. They were physics objects that would bounce off surfaces and walls. If you lost rings, you had 15 seconds to collect them before they disappeared. Before disappearing, they would blink, and if you failed to collect them, they would vanish. Now that you have an understanding of rings in the game, let me explain the mechanic. When there is a line or curved line of rings, you can fast collect them by traveling in their direction. Let me explain in more detail. When there is, for example, a line of rings and you are close to them, you can press the "X" button, and your hero will travel along that line, collecting the rings. Isn't that cool? The rings can even form a curved line to create a 360-degree loop, and the player will still travel through them. This mechanic works in both directions, just like in the original game.

The third mechanic was expanding the functionality of a dash panel (which I described in the first mechanic about the 360-degree loop). In the original game, there were not only panels that increased the player's speed but also panels that propelled the player through the air to cover large distances where there was no ground below. Similar to the original game, I implemented it in a way that the player couldn't take action while being propelled by the force of the panel.

The fourth game mechanic, although more like AI than a mechanic, has some patterns that resemble mechanics. It involves enemies that chase you when you are within their range and attack if you are in front of them. There is more to these enemies, such as their animations and attacking methods, but that will be covered in another mechanic.

Fifth, there are springs in the game that accelerate the player upward upon collision.

Sixth, Homing attack. If you asked what my second favorite mechanic is, I would definitely say that it is the homing attack. When you press the "Space" button or are in the air by spring acceleration, you can press the "Space" button to homing attack the closest enemy or the closest spring. When your hero is homing attacking, he is immune to damage. Like in the original game, when the player homing attacks an enemy, he will be accelerated up, and when he homing attacks a spring, he will be accelerated up by the spring.

Seventh, gun shooting and reloading. The hero you are controlling has a gun in his right hand that can shoot by pressing the "Z" button. When you shoot, a shooting animation will play, as well as the sound of the shot, and a bullet will come from the gun. The bullet can collide with enemies. That action will destroy the bullet as well as the enemy. After shooting, you won't be able to shoot again for a while. You will be able to shoot again when the hero reloads the gun. You will notice that you can shoot again by the reloading sound. I understand that Sonic games are more about speed, platforming, and adventure, and in other Sonic games, that mechanic was never implemented again. I really liked adding another option to destroy enemies.

Eighth, even though it's not a mechanic at all, I want to mention that I added animations, sounds, and other visual effects to enhance the gameplay experience. These

# What distinguishes this project from others in the course and defends its complexity?

While my project has something in common with other projects that were in this course, such as GUI as in 'Helicopter 3D' or character movement like in 'Dreadhalls' or gun shooting like in 'Portal,' the mechanics are slightly different. For example, my project has a third-person controller with a rotating camera focused on the hero, whereas 'Dreadhalls' used a first-person controller. In 'Portal,' the gun didn't have projectiles on shoot and didn't have enemies that interact with enemies. All the mechanics that I mentioned above were implemented by myself and were not present in any other game taught in this course.

This project taught me how to work with Unity's animator for animations and transitions, as well as sound and music integration. I learned how to create fully functional drag-and-drop prefabs to simplify level creation. It's much easier and more efficient to create something reusable and then use it by simply dragging and dropping. For example, I created an enemy robot prefab that can be dragged from my folder into the scene, and it will work with anything else. I also created packs of rings, both vertical and horizontal, that can be easily placed in the scene and rotated as desired, and the mechanic for traveling through rings will work seamlessly. The same applies to my spring prefab.

I also learned not only how to drag and drop prefabs but also how to instantiate them in code. For example, in shooting actions, the bullet prefab is instantiated and flies from the gun. I also gained a lot of knowledge about position, rotation, and quaternions. Let's take the example of the ring mechanic again. When you want to travel through them by pressing 'X,' you need to determine the direction the player is facing, whether forward or backward, to travel through the rings in the proper direction.

Furthermore, I learned a lot about rigid body physics in Unity, such as adding force to the player when they accelerate on dash panels or fly in an accelerated direction. I also did that the player accelerates faster on declined surfaces than on inclined ones. Of course, the player controller script was the most challenging part. I organized it in a way that inputs are in the Update function, physics calculations are in FixedUpdate (as recommended by Unity), and animation logic changes are in LateUpdate. The character controller is hand-written from scratch by me and consists of over 300 lines of code without repeating chunks. Through this project, I not only strengthened my knowledge of delta time but also learned why physics calculations in FixedUpdate should use fixedDeltaTime.

The main feature found in all Sonic games, the 360-loop running, was achieved through raycasting, RaycastHit, and hit position, which, in my opinion, is a very important skill. The camera that follows the player and can be controlled by mouse rotation after left-clicking the mouse to rotate the camera in-game was never taught in other projects and was implemented entirely by me.

With all that, I believe my project defends its complexity and distinguishes itself from others.

### How to controll player

| Input                    | Action                                   |
|--------------------------|------------------------------------------|
| `W`                      | Move forward                             |
| `A`                      | Rotate left                              |
| `D`                      | Rotate right                             |
| `Space`                  | Jump                                     |
| `Z`                      | Shoot                                    |
| `X`                      | Fly through rings                        |
| `LMB`                    | Rotate Camera                            |
| `Space` + `Space`        | Attack                                   |
