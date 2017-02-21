# starboundQuests
Experiments with Starbound's generated quests system. Each folder is a mod that adds a single type of quest. Each of these mods also adds a 'questy' .npctype that will offer the generated quest and generates quests at a higher rate.

## Mission Quests
The example quest uses the "Floran Arena" dungeon as a mission. The npc giving the quest will teleport the player to the given mission. The mission will be marked as completed and ready to turn in when the player is close enough to a goal entity that has the "goalEntityUid".
### Improvements Needed/Problems found
 * Doesn't pull from a list of dungeons - a new questtemplate is needed for each mission
 * Doesn't hook into the generated quest chains - need version that can provide materials for other quests
 
## Fetch Quests
This example creates a 'blacksmith themed' set of items that the npc will request the player to fetch. The example template draws from fetechSmithy.config - which is listed as fetchSmithy in the pools list.
### Improvements Needed/Problems found
 * Nothing yet! *fingers crossed*
