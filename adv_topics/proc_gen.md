# Procedural generation advanced topic presentation outline

## Presentation 1
* Introduction (approx. 10-15 min.)
	* Description of what procedural generation is and why it is used
	* Examples of procedural generation in popular video games
		* Random pick from set of possible "room designs" in Spelunky for each room
		* Minecraft (biome-style generation)
		* Binding of Issac ([info here](https://bindingofisaacrebirth.fandom.com/wiki/Level_Generation)) 
		* etc.
* Topic 1 - Analyzing procedural generation in dungeons (20 min.)
	* Summary of research [paper](https://www.researchgate.net/publication/260800341_Procedural_Generation_of_Dungeons)
	* Process/design structure
	* Retrospect
* Topic 2 - Implementing procedural generation (10 min.)
	* Cellular automata for interior room generation
	* Maze algorithm for dungeon pathing (one room to another)

## Presentation 2

* Introduction (approx 5 min.)
	* Quick recap of maze generation 
		* Key Terms
	* How pokemon & runescape use procedural generation
* Topic 1 - Deep dive into Ellers algorithm (20 min.)
	* Overview of Ellers algorithm
		* Relevant background information
		* Eller's algorithm use cases
	* Explain Pseudocode
	* Run-Time Analysis
	* Performance Costs
	* Comparison of Ellers algorithm to other maze generation algorithms
* Topic 2 - Our Implementation of  Ellers algorithm (20 mins)
	* Where we implemented Eller’s algorithm
	* Implementation details on our Gym Mazes
		* Three Mazes in each gym 
	* Implementation of Spawnable Monsters on Map
		* Random Spawn Locations 
	* Roadblocks/Advantages in our Implementation	 	
...

