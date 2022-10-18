# AlgorithmAndParser for ECE 3422
These files take in .txt files and converts them into .csv files and then pyamaze mazes. It also uses A*star to search for a correct path from the origin to elsewhere. This path gets turned into a txt file as well. This module will also go over important information from the pyamaze module itself.


**Generate a Maze:**
To simply generate a maze, you need to create the maze object and then apply the ***CreateMaze*** function. The last statement will be applying the function ***run*** to run the simulation.
```
from pyamaze import maze
m=maze()
m.CreateMaze()
m.run()
```

A random 10x10 maze will be generated like this:

![Sample 10x10 Maze](https://github.com/MAN1986/pyamaze/blob/main/Picture1.png)

This is what our expected results should look like in terms of a maze after the first class. The second class is designed in order to create the path and export it to a .txt file. Code to run the maze looks like this.

from pyamaze import maze
m=maze(5,5)
m.CreateMaze()
m.run()

