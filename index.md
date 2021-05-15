# Wall-following-vehicle
This an AGV based project implemented in webots platform

This project comprises of three different robotic cars which tracks and follows walls. It also has an camera which helps it to identify a visual marker and stop. Once a robotic car (say Car A) reaches it's destination by tracking walls, it autonomously commands the next robotic car to move and while tracking the walls the robotic cars also avoid the obstacles placed in their route. In addition to wall following with obstacle avoidance and visual marker identification features, they also communicate with each other.

# Robot Model
The picture below shows the robot.
![6wb](https://user-images.githubusercontent.com/71832455/118360134-edde5600-b5a3-11eb-87df-4e255700222c.png)

# Sensors Used
I have modelled all the sensors that I have used for my robotic cars instead of incorporating the pre-existing "proto-sensors" and by this I mean, I designed it's outlook without using the various complete sensor models available. I have used distance sensors for both tracking the wall as well to avoid obstacles. To establish communication between them, I have modelled and used emitter-reciever modules. To detect the visual markers, I have used a camera.

# Working
Check out the video given below


https://user-images.githubusercontent.com/71832455/118361030-30edf880-b5a7-11eb-9b0d-4819b7e7c6ea.mp4

To know more about this project, click on the "view on github" button on the top of this page.
