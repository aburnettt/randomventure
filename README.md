# Random Adventure Game
## An experiment 
The goal of this project is to build an engine capable of generating random adventure games that contain a coherent narrative and a high degree of randomness. 

## Engine meets Data
The data will drive the nature of the engine. All mechanics of the random adventure games are broken into categories. The content of each of these categories can be added to at will, meaning once the engine is complete, datafill can be done indefinitely by any number of parties. It is the responsibility of the engine to draw upon this data sufficiently

## Categories
All data is one of the following categories:

* Plot
* Character
* Actor
* Chapter
* Puzzle
* Cutscene
* Map
* Trap

## Database
This data will all likely best fit in a database, where each item has several tags, and these tags can be searched. Any attribute of the item may be searched. For instance, the third part of a certain plot may demand a puzzle where an item is required, the Shopkeeper is involved, and the reward is a bag of gold. These requirements are defined in the plot, and the data of the other objects must support this query. 
