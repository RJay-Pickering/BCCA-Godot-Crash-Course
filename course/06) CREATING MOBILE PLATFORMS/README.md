# CREATING MOBILE PLATFORMS
Creating mobile platformers is a fun and challenging addition to 2D platformers in Godot 4.0. Mobile platforms can add variety and complexity to your game's levels. Here are the steps to create mobile platforms:

**1. Setting up the mobile platform:**

- Create a new node in your scene (e.g., an "Area2D" node for the mobile platform).
- Add a sprite to represent the look and feel of the platform.
- Add a "RigidBody2D" or "KinematicBody2D" as a child node to control the movement of the platform.

**2. Setting Up the Motion:**

- On the "RigidBody2D" or "KinematicBody2D" node of the mobile platform, add a new "AnimationPlayer" or "Tween" to control the movement of the platform.
- Define the trajectory of the mobile platform. This can be done by using keyframes in the "AnimationPlayer" or by using tweens in the "Tween".
- Configure the platform's speed, duration, and motion trajectory.

**3. Collision Logic:**

- Make sure the moving platform has a "CollisionShape2D" set up for collision detection with the player and other in-game objects.
- Implement collision logic to ensure that the player can stay on the moving platform. This usually involves changing the player's position so that they move along with the platform.

**4. Adding Extra Behaviors:**

- If you want, you can add extra behaviors, such as activating switches to control the movement of the moving platform, or adding obstacles that block the platform's path until certain conditions are met.

**5. Testing and Adjusting:**

- Run the game and test the movement of the moving platform to make sure it works as intended.
- Adjust the speed, trajectory, and other parameters until you get the desired effect.

**6. Export:**

Make sure that the mobile platform and its features are set up correctly in the exporter so that they are included when you export the game to the desired platform.

Creating mobile platforms adds dynamism to your levels and challenges for the player. Practice and experimentation are key to honing your skills in creating mobile platforms in Godot 4.0. Be sure to refer to the official Godot documentation for more details on how to create movable objects in this release.