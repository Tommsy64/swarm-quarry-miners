# swarm-quarry-miners
HTTP controlled turtle swarm quarry

A ComputerCraft system that allows you to set up cheap, efficient, scalable mining operations.

Turtles communicate with a node.js server to coordinate mining at a minimal resource cost.

The server code will be released later once it is working properly.

## Todo
* Write setup program
* Patch dropoff code to put fuel into the fuel chest if possible
* Fix bug where turtles will start mining at the spot they are placed - should move forward one block
* Make relgo's goto function less aggressive (breaks turtles too often) and improve pathfinding
