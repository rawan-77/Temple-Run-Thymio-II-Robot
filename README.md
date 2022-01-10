# Temple-Run-Thymio-II-Robot
A program (using ASEBA) that allows Thymio II robot to navigate a temple maze and get to a treasure room by scanning barcodes on the walls of the maze. Barcodes resemble instructions such as which direction to go and what color to light up.

## Detailed Description

### The Course - Source: CSCI 1108 - Professor Mitchel Kane - Brightspace - Dalhousie University
The blue arrows indicate removable blocks and the red ovals indicate barcodes. Before testing the program, some of the removable blocks are removed to provide a path for the robot to follow. The barcodes resemble instructions. The program allows the robot to scan these barcodes to know which path is open. One of the barcodes indicates a color and as soon as the robot scans it, it lights up. At the hazard lines, the robot stops and beeps for 5 seconds then continues moving to find the treasure room. It follows one of the black lines based on the barcodes' instructions (which path is open). The purple circle is inside the treasure room, where the robot should stop.  

![The Course](https://user-images.githubusercontent.com/97373344/148852635-9af730f8-fa5e-4f5f-b8c4-091fe7072682.png)


## How the code works in the simulator
The following video shows how the code works in the simulator. It does not light up at the hazard lines and it does not stop at the circle in the treasure room like it should because at the time of making this video, these two features were not added to the code yet. However, these two features are now present in the code. 



https://user-images.githubusercontent.com/97373344/148851544-a9ccc5ca-07ae-4dda-bd62-e40d9c73d4a8.mp4

