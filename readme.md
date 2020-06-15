SPIDERBOT 

Spiderbot is an open source project which aims to produce a scalable control structure for multi-pedal robots. 

Planned work includes:
	- development of a leg controller which is scalable to the number of joits specified in the leg by a user
	- development of a movement planner which is capable of sending commands to each leg controller given an input command (cmd_vel, but could be subsequently replaced by motion primitives)
	- a suite of motion primitives such as jumping, strafing, movement, etc which will eventually be used to implement a streamlined, 'modular', control scheme
