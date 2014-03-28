Limb-Provement
==============

Simple algorithm, many implementations.


###Authors###
- Taylor Peet
- Christa Peet
- Julie Gordon


###Goal###
In order to experiment with new languages, technologies, and user interfaces, implement a simple algorithm in each, according to the best practices of technologies involved.

####Goal in plain English####
Write the same simple code in new languages with best practices of that language to help start learning that language.

####Stretch Goal####
Implement the smarter, dynamic programming approach in each language.

###Scenario###
You have started a project that requires several pieces of wood of different lengths. You will need to cut the larger pieces you buy at the store into the desired lengths, but would like to minimize the cost by buying the smallest number of boards that, when cut, produce some waste and all of the lengths for the project. 

###Simple Algorithm###
- Pick a target board size
- Repeat until all desired cut lengths have been considered
	- Add desired cut lengths to an existing board with enough free space remaining
	- If no board exists, create a new board and add to that board
- Output number of boards and where to make cuts on them