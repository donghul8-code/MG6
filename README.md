# MG6
1. The entire for loop will complete before the Update method finishes. It will make the game lag because Update needs to wait for the for loop to complete before moving to the next frame.
2. One issue is that the player can pass through walls by jumping. This happens because the logic disables the player's collider whenever the player is moving upward. Since the collider is completely disabled, the player can pass through any object, not just platforms.

