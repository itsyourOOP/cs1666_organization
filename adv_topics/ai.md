# AI advanced topic presentation outline

## Presentation 1

* Introduction (10 min.)
	* General overview of artificial intelligence
	* Relevant background information:
		* games/Game theory
		* zero-sum games
		* utility
		* adversarial search
		* evaluation function
	* Examples of adversarial search in games
		* Deep Blue (Chess game)
		* Go
		* Tic tac toe
* Topic 1 - Deeper dive into minimax, an adversarial search algorithm (25 min.)
	* Overview of the core components of the algorithm
		* Assuming perfect information for both players
		* Performance costs (Space complexity, Time complexity)
		* Using pruning to reduce possible choices
		* An example of a minimax tree and its result
	* Alpha/Beta iteration of minimax search
		* Improvements over regular minimax search
			* Performance costs (Space complexity, Time complexity)
			* Doesn’t need to search through whole game space
			* More efficient pruning
		* An example of alpha-beta pruning’s improvement upon minimax
	* Depth limited minimax
* Topic 2 - Specific Implementations of AI in Monster Fighting Games (10 min.)
	* Pokemon Generation 1 AI Implementation
	* Our proposed AI improving upon Pokemon

## Presentation 2

* Introduction (5 min)
	* General introduction of what it is
	* Psuedointelligence vs artificial intelligence
		* Psudeointelligence mimics what we think of AI, it gives enemies and NPCs
			directions, giving the appearance of AI
		* 'True' AI actually learns from the game itself and the player to improve itself		
* Different types of AI (quick introduction) (5 min)
	* Stateless AI
	* State Machine AI
	* Neural Networks
		* Deep Learning and the training process to improve in-game AI
* Topic 1 - Deep Dive of State Machine vs Machine Learning (Neural Networks) (15 min)
	* Discussion of a traditional State Machine and their approaches
	* Discussion of Machine Learning and different implementations and use cases
	* How the two types of AI are different, but how they can also work together
* Topic 2 - Our Approach for the AI engine (20 min)
	* What type of AI we decided on (an advanced state machine)
	* A coordinated approach to AI, where the enemies work together based on enemy type
		and the current status of the player
	* Troubles we ran into developing a coordinated approach
...
