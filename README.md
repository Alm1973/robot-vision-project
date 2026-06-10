# Adaptability of VLMs in Robotic Control Systems

## Project Title
Robotic System for Object Detection

## Project Description
For the current project, we have designed a vision based robot control system which involves the use of a camera, VLM, and a robotic arm controlled by the microcontroller. The system is supposed to identify objects within a workspace, get their location from the processed images, and actuate physical movements through the use of an Arduino actuation system and guide the robotic arm there.

## Research Question
Can a locally run Visula language model recover from task disrupting situations such as a, including occlusion,changes in its environment , and abnormal targets, by allowing dynamic reasoning and adaptive camera repositioning strategies. The study will push a fixed set of failure factors into a defined object verification task, and measure whether the model detects the failure, adapts its plan, and ultimately completes the task on its own.

## Current Hardware Setup
- Arduino Uno 
- USB camera / webcam mounted above workspace
- Robotic arm (servo-based, 4 DOF)
- Servo motors for movement
- USB connection between computer and Arduino
- Laptop running Python (OpenCV + Moondream)
- PCA9685 16-Channel PWM Servo Driver
- UBEC 

## How to Run the Code
