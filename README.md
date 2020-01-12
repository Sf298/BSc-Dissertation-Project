# BSc-Dissertation-Project
This is a project I made for my BSc thesis.

It is a first person game where the player must navigate a dungeon themed maze to collect loot, while avoiding hostile AI, a randomly shifting maze and other obstacles. Player movements were also tracked and modelled to identify which strategy they could be using. If the project had been completed (not finished due to time constraints), this would have allowed an additional AI to cut players off and herd them toward traps.

The maze has the ability to randomise itself with out indicating to the player to realise that anything has changed. It does this by ray-casting out from the player to detect all the walls that could be visible. By marking these walls as "generated" the maze can be randomised like it normally would, making it seem as though nothing had changed.

The maze has 2 NPCs that wander around until the player is detected. The first uses line of sight at any distance while the second uses audio to detect the player's footsteps (even through walls). Both run towards the player's last known location so that players cannot escape by running around a corner.

# License
This project is meant to be viewed only. I do not provide permission to use, modify, or share the code, assets (images, models, sounds, etc.), or any other IP found in this project.
