# AI-Based Python Project for Shotest Path Finder
Uses the concept of BFS(Breadth First Search) to find out the shortest path between start and end point. 
![image](https://github.com/Vivekauti17/AI-mini-Project/assets/142137729/afb3cc35-425e-4e02-a7b9-312d3ab1055f)
Green box indicating starting point.
![image](https://github.com/Vivekauti17/AI-mini-Project/assets/142137729/73566a31-eeb6-4928-98c4-d85fe63a8b9d)
Blue box indicating ending point.
![image](https://github.com/Vivekauti17/AI-mini-Project/assets/142137729/5683ee32-990e-467b-a546-ffce0a4175e8)
Red boxes indicating Hurdles.
![image](https://github.com/Vivekauti17/AI-mini-Project/assets/142137729/b1c41c21-a9d4-4394-8c19-d8a640eff42f)
Black line indicates the Shortest Path to reach its destination.


# About the Program
A window is opened in front of the user once this program is runned.
A set of quick instructions is provided at the top of the window.
A grid is present on the window , where the user can put the starting and ending point by choosing the respective key on the keyboard and clicking on any block of the grid. 
User can also place hurdles(obstacles) one by one in the grid, by clicking in the particular position in the grid.
Each press of 'r' in the keyboard places 100 hurdles(obstacles) at random positions in the grid.
After that the user can hit the "spacebar" to see the program finding out the shortest path between start and end point.
Press 'o' to clear the grid.
# About the Python Modules used in this Project
Turtle: To do the overall visualisation of the entire process
Tkinter: To show info if there is not path available between start and end points 
random: to place the obstacles randomly at any point of the grid
numpy: to create 2d arrays to be used as adjancency matrix , also used in making some other necessary arrays.
