# NASA-Mars-Rover-Project
For at least three decades, scientists have advocated the return of geological samples from Mars. One early
concept was the Sample Collection for Investigation of Mars (SCIM) proposal, which involved sending a
spacecraft in a grazing pass through Mars's upper atmosphere to collect dust and air samples without
landing or orbiting.
As of late 1999, the MSR mission was anticipated to be launched from Earth in 2003 and 2005. Each was to
deliver a rover and a Mars ascent vehicle, and a French supplied Mars orbiter with Earth return capability
was to be included in 2005. Sample containers orbited by both MAVs were to reach Earth in 2008. This
mission concept, considered by NASA's Mars Exploration Program to return samples by 2008, was cancelled
following a program review
In this project, we’ll do computer vision for robotics. We are going to build a Sample & Return Rover in
simulation. Mainly, we’ll control the robot from images streamed from a camera mounted on the robot. The project aims to do autonomous mapping and
navigation given an initial map of the environment. Realistically speaking, the hard work is done now that you have the mapping component! You will have the option to choose whether to send orders like the throttle, brake, and steering with each new image the rover's camera produces.

![WhatsApp Image 2023-01-03 at 10 16 34 PM](https://user-images.githubusercontent.com/84942322/210434793-d13ed61f-d5a8-473d-a801-29db4790251c.jpeg)

To run this project follow the following steps
# Needed Python libraries to be installed
- OpenCV
- numpy
- matplotlib
- socketio
- flask
# To run the automated code with the Rover simulator
- in code directory run command: source ~/anaconda3/bin/activate root to activate the anaconda environment
- then run the command: python drive_rover.py
- Start the simulator (Roversim.x86_64 or Roversim.x86) and choose "Autonomous Mode."
