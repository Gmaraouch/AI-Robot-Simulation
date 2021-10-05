# AI Robot Simulation on C++
 
 Credits:  
 Ghassan Maraouch  
 Austin McLean  
 Glen Alfred  
 Taran Raina  
 
This project is a simulation for an AI robot using computer vision. The program features 2 robots; one of them will be in the offense (chasing) and the other will be defending (running away). The robot in the offense has the objective of shooting a laser at the target located on the second robot. A maximum of 2 shots are allowed per run of the program. The objective of the AI is to:  
1. Be able to chase after the defending robot while avoiding collision with the other robot and avoiding any obstacles.
2. Determine when to take a shot with the laser to try and hit the defending robot. The laser cannot be shot through obstacles. 
3. Avoid running out of bounds  

The path finding is done by using A* or artificial potential field. A* is used for attacking and artificial potential field for defending. To run the program, run "image_view.exe" and then run the solution file. 
