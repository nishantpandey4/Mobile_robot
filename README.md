The package consists of:

Assembly file in zip format containing the assembly file and parts (the 
.STLPRT files),

Package(updated_assembly) to run 

--> The updated_assembly consists of all the files required to run the bot on Gazebo and RViz, also the code to run publisher.py and subscriber.py and teleop_template.py code in the src folder of the same.

The robot in the world can be launched using the command:

--> roslaunch updated_assembly updated_assembly.launch

To launch and run the robot on the empty_world comment line in which competition_world is included and run the same command above

Create a catkin_ws and build it, then source it

--> Download the package

--> Paste the package into the source directory(src)

--> Build and source the workspace:
	catkin_make clean && catkin_make

--> Commands to run (open separate terminals and run in the same order) 

  roslaunch updated_assembly updated_assembly.launch

  python3 publisher.py ( navigate to the updated_assembly folder in the terminal then run the command)

  python3 subscriber.py ( navigate to the updated_assembly folder in the terminal then run the command)

  Python3 teleop_template.py ( navigate to the src folder in the updated_assembly folder in the terminal then run the command)

Videos of the execution:


https://github.com/nishantpandey4/Mobile_robot/assets/127569735/015c18c3-faf7-44e2-ba65-90b055de5e15



https://github.com/nishantpandey4/Mobile_robot/assets/127569735/a65cd910-7d4a-4e5d-9638-ffe5c709b775

