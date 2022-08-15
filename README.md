# Facial Gesture Controlled RC Car

The aim of the project was to provide an alternate solution for people suffering from problems which rendered them unable to drive a vehicle using either of their limbs.

Objectives:
1) At the edge computing end, a MediaPipe FaceNet model will create a facial landmarks net, which will help with the gaze tracking part of the project. The gazes in different directions will help understand which direction is the car steering supposed to be carried out in.
2) Connect the decision system from the edge device to the raspberryPi using MQTT Client broker code.
3) The decisions obtained on the rPi should then be used to provide specific voltages to different pins on the rPi, which then in turn will drive the motor drivers to have the wheels rotate accordingly. (code not included)
