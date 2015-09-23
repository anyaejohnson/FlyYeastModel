This is a repository for a proof-of-concept simulation of a mutualism between Drosophila and Yeast. 

fly.py contains the class for Fly objects. Flies are able to ‘move’ to a new location within the world, ‘eat’ yeast at their current location, ‘reproduce’, and ‘update’ i.e. proceed through a unit of time. 

yeast.py contains the class for Yeast objects. Yeast have a sporulation probability that is tested at every time step and otherwise they reproduce at that time step.

world.py contains the code for the artificial life simulation of the fly and yeast world. It creates a population of flies and yeast and runs through the number of time steps specified by the user. To set the size of the fly population, change NUM_FLY. To set the size of the yeast population, change NUM_YEAST_COL. To set the size of the world (i.e. how many open cells there are compared to the yeast population), change WORLD_SIZE. To set how many time steps the simulation runs for, change NUM_UPDATES.