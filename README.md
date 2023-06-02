# Assignment 2: Two-Wheeled Mobile Robot (Jupyter Notebook)
This is a simple, two-wheeled mobile robot that is coded and developed by **Natnael Berhanu Takele** using the jupyter notebook.

## Assignment Description
There is a node which implements an action client, allowing the user to set a target (x, y) or to cancel it. This node
also publishes the robot position and velocity as a custom message (x,y, vel_x, vel_z), by relying on the values
published on the topic /odom. What we are asked in this assignment is to create a jupyter notebook to replace the user
interface. 

## Expected Result
In the final implementation, the notebook is supposed to incorporate several elements to facilitate the interaction and visualization of the robot's motion in the environment. These components are:

1. **Buttons for Robot Motion** - The notebook will include buttons that enable the user to control the robot's movement within the environment.
2. **Plot of Robot and Targets' Positions** - A plot is generated within the notebook, showcasing the positions of both the robot and the targets in the environment. This plot provides a visual representation of the robot's location and the location of the targets relative to it.
3. **Text Box for Closest Obstacle Distance** - A text box is supposed to be included in the notebook, displaying the distance to the closest obstacle detected by the robot's laser scanner. This information helps the user assess the proximity of obstacles and make informed decisions about the robot's movements.
4. **Plot for Reached/Not-reached Targets** - Another plot will be expected to be generated to illustrate the number of targets reached versus the number of targets not reached by the robot. This plot provides an overview of the robot's performance in completing its task of reaching the targets within the environment.

## Conclusion
By incorporating these elements into the notebook, users can interact with the robot, visualize its position and targets' positions, monitor obstacle distances, and assess the overall progress in reaching the targets. This comprehensive set of features enhances the usability and functionality of the notebook for studying and analyzing the robot's behavior and performance in the given environment.
