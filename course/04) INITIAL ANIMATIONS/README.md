# INITIAL ANIMATIONS
Adding initial animations to a 2D platformer in Godot 4.0 can make the game more dynamic and compelling. Here are the basic steps to create starter animations in your 2D platformer:

**1. Preparation:**

Before you can start creating animations, you must have the necessary graphic assets, such as sprites for the character, enemies, objects, and other elements of the game.

**2. Creating Animations:**

Creating animations in Godot 4.0 involves the use of the Animation Editor. Follow these steps:

- In Godot, select the node of the character or object you want to animate in the Scene Tree. 
- In the Inspector, go to the "Animation" tab and click the "AnimationPlayer" button to add an AnimationPlayer to the node. This allows you to create and manage animations for the object. 
- In the AnimationPlayer, click the "Animation" button to create a new animation. Give the animation a name. 
- With the animation selected, click the "Record" button to activate the recording mode. This allows you to make changes to the object and record the keyframes of the animation.

**3. Creating Keyframes:**

Now, you can create keyframes for the animation. This involves setting object properties (position, scale, rotation, etc.) at specific moments in the animation. For example, for a character jump animation:

- Advance in the timeline to the moment when the character starts jumping. 
- Change the character's Y position to represent the jump. 
- Add a keyframe for that position. 
- Progress through the timeline to the moment when the character returns to the ground. 
- Set the Y position back to the original value and add another keyframe.

**4. Playing and Testing the Animation:**

You can play and test the animation in Godot to see how it looks. Be sure to adjust the animation speed, number of repetitions, and other parameters as needed.

**5. Game Logic:**

Depending on the game's interactions, you can use scripts to control the start and stop of animations. For example, character jumping can be triggered by a script when the player presses the jump key.

**6. Export:**

Make sure that your graphics and animations are set up correctly in the exporter so that they are included when you export the game to the desired platform.

Keep in mind that creating animations is an important part of creating compelling 2D games in Godot 4.0, and practice and experimentation will help hone your skills in creating animations for your platformer. Be sure to refer to the official Godot documentation for more details on creating animations in Godot 4.0.