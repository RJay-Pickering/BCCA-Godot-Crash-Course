# CRAFTING COLLECTIBLES
Creating collectibles in a 2D platformer in Godot 4.0 is one way to add elements of challenge and reward to your levels. Here are the steps to create collectibles:

**1. Resource Preparation:**

Before you begin, you must create the graphic assets for your collectibles, such as sprites for coins, power-ups, or any item that players can collect.

**2. Creating the Collectible Item Node:**

- In Godot, create a node in your scene that represents the pick-up item (for example, an "Area2D" node).
- Add a sprite to the node for the item's appearance.

**3. Adding Collection Logic:**

- Add a "CollisionShape2D" to the item's node for collision detection with the player. 
- Make sure the player has a collision mask that allows them to interact with pickups.

**4. Script for Collection:**

- Add a script to the collectible item node to handle the collection logic. 
- Use the '_on_ ' function to detect the collision with the player. For instance:

```GDscript
func _on_Area2D_body_entered(body): 
    if body.is_in_group("player"): 
        # The player collided with the pick-up 
        # Run the collection logic here queue_free() 
        # Destroy the pick-up
```

- In the collection logic, you can update the player's score, apply effects, or do any desired action.

**5. Testing and Adjusting:**

- Run the game and test the item collection to make sure it works as expected.
- Adjust the value of collectibles and other properties as needed.

**6. Adding More Items:**

Repeat the previous steps to create different types of collectibles, if desired. You can create different classes of collectible items and set unique properties for each.

**7. Export:**

Make sure that collectibles and their assets are set up correctly in the exporter so that they are included when you export the game to the desired platform.

Collectibles are an effective way to create an in-game goal, such as collecting coins or power-ups, and provide players with a sense of progress and reward. Practice and experimentation are important to hone your skills in creating collectibles in Godot 4.0. Please refer to the official Godot documentation for more details on using collectibles in this release.