# find-shortest-path
## Description:
Determines the shortest path on from a power station to a new customer on an electrical grid map using doubly linked lists (extension of find-valid-path)

## Notable files:
The main method is in "FindShortestPath\src\ShortestPath.java"
Sample maps of the power station electrical grid inputs are included in "FindValidPath\input\.." (maps 6-8 do not have a path from the power station to the new costumer house)

## Prequisite:
Eclipse IDE

## Prepare for Deployment:
*Specify which power station map to be used as input using "Run Configurations"*

 The arguments tab in "Run Configurations" should contain the location of the input file/image:

 Examples arguments include:
 C:\Users\Eliza\FindShortestPath\input\map1.txt 
  
## Deployment:
Once the program is run, a window showing the electrical grid, the power station,omni switches,horizonal/vertical switches neighbouring houses and the new customer house should pop up. The program will use a blue block to show the path that is being actively being tested.A red bluck with an electrical symbol shows the shortest path found.When the program is done the console will indicate how long the shortest path is.




