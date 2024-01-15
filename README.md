# TMR-Soccer-Junior
This repository contains some of the work I made for the team Galacticos for the Mexican Robotics Tournament 2019.

We participated in the Robocup Soccer Open Junior category. Here we had to develop two soccer player autonomous robots.

In the gif below you can see how one of our robots scored a goal.

<p align="center">
<img src="https://github.com/alejandro3141592/TMR-Soccer-Junior/assets/132953325/2d8c0385-22ec-40cd-8930-c57a26f3acd0"/>
</p>

In the image below you can see in detail one of our robots.

You can see this robot has a lot of sensors, circuits, and actuators, so the main parts of the robot are described here:
- Arduino Mega: This is the microcontroller, the brain of our robot.
- PixyCam: This is the sensor we used to detect the orange ball and the goals.
- Battery: This provides the main source of energy of our robot, necessary to run the five motors for at least 20 consecutive minutes.
- DC motors: We have four of them to drive the robot using omnidirectional wheels.
- Dribbler: This is the bar at the front of the robot in charge of making spin the ball, since the rules state that the ball must move freely if a robot has possession of it. We use a brushless motor to spin it.
- Compass: At the top of the robot. We use it to orientate the robot to the front.
- Mirror: We use it with the camera, to have a 360° view of the field.
- Light sensors: We have them at the bottom of the robot, to detect the white lines in the field.
- Kicker: We use a selenoid to kick the ball when we have a clear shot

<p align="center">
<img src="https://github.com/alejandro3141592/TMR-Soccer-Junior/assets/132953325/7d162306-2de0-4c5f-aa58-e3c5eeb70fd9"/>
</p>
