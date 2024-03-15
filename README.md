# Group-Lab
## Instructions:

### Objective:
The objective of the Group Lab game is to collect resources and complete experiments to advance scientific research.

### Mechanics:

1. **Resource Collection:**
   - Algorithm:
     ```
     function collectResources(player):
         if player.location == resourceLocation:
             player.inventory.add(resource)
     ```
   - Example:
     ```
     If player is at the resource location:
     Add resource to player's inventory.
     ```

2. **Experiment Completion:**
   - Algorithm:
     ```
     function completeExperiment(player):
         if player.inventory.containsAll(experimentRequirements):
             player.score += experimentScore
     ```
   - Example:
     ```
     If player has all required resources:
     Increase player's score by experiment score.
     ```

### Your Role:
I, Fyzul, am responsible for developing the game mechanics, implementing algorithms, and ensuring smooth gameplay.

## Continued Development:

Throughout the development process, I will continue to use GitHub for version control and documentation. I'll regularly update the README file as the project progresses, incorporating any changes or additions to the game mechanics.
