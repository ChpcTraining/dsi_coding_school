# Introduction

This section covers the **robotics**. We will first do a brief over of robotics that was captured from the powerpoint presentation, the full presentation can be found the "presentations" folder.

Then we will start with the using Scratch for Arduino and show you how it works.

Lastly, we will focus on building and testing the Robotic Arm project that each person needs to do.

# Robotics Overview

Definition: Robotics is the interdisciplinary field that involves the design, construction, and operation of robots.

Core Components:
- Mechanics: Structure and movement
- Electronics: Power and control systems
- Programming: Logic and decision-making

  ![image](https://github.com/user-attachments/assets/30f99566-2dcb-4bf5-a03a-23285b114e71)

It is key to STEM Learning where it combines science, technology, engineering, and mathematics in an engaging way. Many career opportunities exist and it prepares students for future tech-related jobs. There are various  skills that it teaches:
- Problem-solving
- Critical thinking
- Collaboration
- Creativity & Design
- Artificial Intelligence (AI) *

## Mechanics in Robotics

Definition: Mechanics refers to the physical structure of the robot—its body, limbs, joints, and gears.

Key Components:
- Frames and Chassis: The backbone of the robot.
- Motors and Actuators: Create movement.
- Wheels/Tracks/Legs: Provide mobility.
- Arms/Grippers: Allow the robot to interact with objects.

Example: A robotic arm uses motors to control the joints, allowing it to pick up objects.

## Electronics (Electrical) in Robotics

Definition: Electronics provide power and control to the mechanical parts.

Key Components:
- Power Supply: Battery or external power source.
- Microcontroller/Microprocessor: Acts as the brain of the robot
- Motors and Drivers: Convert electrical energy into motion.
- Wiring & Circuits: Connect all components.

Example: A motor driver controls the speed and direction of a DC motor based on commands from the microcontroller.

Let us now discuss two key components in detail which are Microcontrollers and Motors.

### Microcontroller

Definition: A microcontroller is like small computer on a single integrated circuit (IC) designed to control devices or processes.

Basics:
- CPU: The brain of the microcontroller that executes programs and instructions. 
- Memory: Used to store instructions and information
- I/O Pins: Connect to external devices, such as sensors, motors, or displays, allowing the microcontroller to interact with the physical world.

![image](https://github.com/user-attachments/assets/9bb77896-fe65-4adb-a2cf-6c46e00384b5)

![image](https://github.com/user-attachments/assets/7f7720d9-3b7b-4fbc-af73-1abfac673a9f)

### Microcontroller vs Microprocessor

**Microcontrollers** are self-contained systems with all components needed for control in a single chip. They are optimized for controlling tasks and are found in everyday devices like microwaves, thermostats, and toys.

**Microprocessors**, in contrast, are more powerful but require external components (like RAM and storage) to function. These are used in cell phones, computers like desktops and laptops

![image](https://github.com/user-attachments/assets/fdf02006-a966-4695-8420-2287f36d24c6)

### Servo Motors

A servo motor is a type of motor that provides precise control of angular or linear position, speed, and torque. 
Unlike regular motors, which simply rotate continuously, a servo motor can be instructed to move to a specific position and hold that position until further instructions are given. 
This makes it highly useful in applications requiring accurate movement and control, such as in robotics, drones, and automation systems.


A servo motor system typically consists of three key components:

- Motor: The electric motor that provides the rotational or linear movement.
- Control Circuit: Receives a signal (usually a Pulse Width Modulation, or PWM, signal) that tells the motor how far to move and in what direction.
- Feedback Mechanism: Usually a potentiometer or encoder that monitors the motor's position and sends feedback to the control circuit. This allows the motor to adjust and maintain its desired position accurately.

![image](https://github.com/user-attachments/assets/2ab87d89-062e-40be-b7cc-3692f9974788)

![image](https://github.com/user-attachments/assets/fd74838a-84b5-4054-963a-5d3ab1322c5e)

![image](https://github.com/user-attachments/assets/c582327a-1364-419b-94ae-ab1a0ce8c795)

## Programming In Robotics

Definition: Programming is the process of writing a set of instructions, known as code, that a computer or other devices like microcontrollers follow to perform specific tasks. These instructions are written in programming languages such as Python, C++, or even visual languages like Scratch.

![image](https://github.com/user-attachments/assets/130ebf2a-dec0-4be5-833e-3edfc434a92a)

Key Components:
- Programming/Coding Languages: C/C++, Python, Scratch
- Control Structure: Loops and conditionals
- Functions: Reusable code
- Sensor control: Real time processing of data from 
environment.

Example: A robot programmed to follow a line uses a loop to 
constantly check sensor data and adjust movement.

## Sensors in Robotics

Definition: Sensors provide robots with information about their environment.

Types of Sensors:
- Distance Sensors: Measure proximity (e.g., ultrasonic, infrared).
- Light Sensors: Detect light and color.
- Touch Sensors: Respond to physical pressure.
- Gyroscope/Accelerometer: Measure orientation and movement.

Example: An ultrasonic sensor helps a robot avoid obstacles by detecting objects in its path.

![image](https://github.com/user-attachments/assets/49c6ed00-1c79-427e-96a8-10fcb40bce49)

## Combining Mechanics, Electronics, and Programming

Example: A line-following robot:
- Mechanics: The robot's chassis and wheels provide mobility.
- Electronics: Motors and sensors are wired to a microcontroller.
- Programming: Code continuously reads sensor data and adjusts the motor speed to stay on track.

Real-world Applications: Autonomous cars, industrial robots, drones.

![image](https://github.com/user-attachments/assets/503d0be9-f8c1-4632-9beb-a717cd6e93fb)

# Real World Applications and Industries

- Healthcare: Medical robots, prosthetics, surgical robots.
- Everyday Life: Vacuum cleaning robots and drones.
- Manufacturing: Automated production lines.
- Agriculture: Autonomous farming equipment.
- Defense & Security: Surveillance and unmanned vehicles.
- Space Exploration: Rovers, space station robotics.

Future Opportunities: As robotics advances, new fields like autonomous vehicles, smart homes, and human-robot collaboration will continue to emerge.

# Careers and Opportunities in Robotics

Growing Industry: Robotics is an expanding field with applications in multiple sectors.

In-Demand Skills:
- Mechanical Engineering
- Electrical Engineering
- Computer Science & Programming
- Artificial Intelligence (AI) & Machine Learning
- Data Analysis

Career Opportunities:
- Robotics Engineer: Design and build robots.
- Automation Specialist: Develop robotic systems for industry.
- AI/ML Developer: Create intelligent robots that can learn and adapt.
- Research Scientist: Work on advanced robotics technologies.

# Robotics in the Classroom

Robotics in Education:
- Hands-on learning that enhances engagement and creativity.
- Develops problem-solving skills through trial and error.
- Encourages teamwork through collaborative projects.
- Integrates multiple subjects: science, technology, engineering, and math (STEM).

Robotics in the Classroom:
- Household Items
- Robotic kits (Arduino, Raspberry pi, etc)
- Use virtual platforms (e.g., Scratch)

## DIY Robotic Hand Using Household Items

Objective: Create a simple robotic hand using everyday materials to teach the principles of mechanics and motion.

Materials Needed:
- Cardboard tube (from a kitchen roll or toilet paper roll)
- Straws (5 plastic straws for fingers)
- String (to control finger movement)
- Tape or glue (for assembly)
- Scissors (to cut materials)

Steps:
- Cut 5 Straws: These will act as fingers. 
- Cut small notches to create "joints" where the fingers will bend.
- Thread String: Thread a piece of string through each straw. 
- Tie a knot at the tip of the straw and leave enough string hanging out the other end to pull.
- Attach to Cardboard Tube: Use tape or glue to attach the straws (fingers) to the cardboard tube (hand base). Ensure the strings are free to move.
- Create Finger Movement: When the string is pulled, the notched straws will bend, simulating finger movement.
- Test and Improve: Experiment by adjusting the string tension and straw positions to improve the movement.

Lesson: This project demonstrates how tendons and muscles work in the human hand, making it a fun, hands-on way to learn about biomechanics and engineering.

![image](https://github.com/user-attachments/assets/f322dab4-61bf-4780-9314-a08c65cda255)

# Next Lesson

If you have gone through this material then please go on to the next section we cover Scratch for Arduino.








