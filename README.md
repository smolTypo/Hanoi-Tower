# Hanoi Tower

<img src="https://github.com/smolTypo/Hanoi-Tower/blob/main/HanoiTower.png" width='400'/>

The Tower of Hanoi is a classic puzzle game that requires the player to move all the discs from one tower to another. This repository contains the Javascript implementation of the Tower of Hanoi exercise, using recursion to solve the puzzle. 

This is an exercise developed during MIT xPro Full Stack Bootcamp.

Live Demo: https://smoltypo.github.io/Hanoi-Tower/

## About:
The Tower of Hanoi is a classic puzzle game in which the objective is to move all the discs from one tower to another. The game consists of three towers (named “A”, “B”, and “C”) and a set of discs. The discs must be moved one at a time, and a disc can only be placed on top of a larger disc. The goal is to move all the discs from tower A to tower C.

The Tower of Hanoi exercise was solved using recursion. The algorithm consists of a base case (when the puzzle is solved) and a recursive step (when the function calls itself with the next set of parameters). The recursive call keeps repeating until the base case is reached. In the case of the Hanoi Tower, the base case is when all the discs have been moved from tower A to tower C.

First, the largest disk should be moved from the first rod to the last rod. This was done by recursively moving the smaller disks from the first rod to the middle rod, then moving the largest disk to the last rod, and then moving the smaller disks from the middle rod to the last rod. This process is repeated until all the disks are on the last rod. 

## How to Run:
You can use the application by pressing the Make Move button. The first press will load the Hanoi Tower. Every button press after that iterates through solving the Hanoi Tower. When the Hanoi Tower is solved, on the last button press, you will receive an alert stating Tower is Finished.

## Future Roadmap:
This is a progression project, no further development is anticipated at this time.

## MIT License:
This project is licensed under the <a href="https://github.com/smolTypo/Hanoi-Tower/blob/main/LICENSE">MIT License</a>.
