# hamster-pathfinding
Pathfinding application for the "Java-Hamster Simulator/Modell"

## How it works
The hamster-pathfinding project uses the "A*" Pathfinding algorithm to find the quickest way to the goal (/ grain).
The path is an integer array and consists of the numbers 0 - 3, where 0 is north, 1 is east etc.

## How to use it
1. Edit the first line of the `hamster.properties` file and set `security=false`
1. Create a terrain file with **one** grain
1. Edit line 25 in Dood.ham
1. Run DoodMain.ham
