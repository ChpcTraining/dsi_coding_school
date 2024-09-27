# Introduction

Objective: We learnt Scratch and how it works, now we are going to connect it to the real world. We are going to connect it to a microcontroller to control the motors of for our robotics arm project.

# Setup Scratch With Arduino

1. Open up S4A (Scratch for Arduino) in Windows

![image](https://github.com/user-attachments/assets/ba292db1-13d3-47f4-9bf2-a0b10e0fd68f)

2. You should see the following:

![image](https://github.com/user-attachments/assets/0567412c-5eb9-4fa2-ad05-f311707b8a81)

We will only be working with Motion and Control:

![image](https://github.com/user-attachments/assets/bdf280b4-11ed-4003-9186-a9dcbd7bbc43)

You will notice Motion has different blocks:

![image](https://github.com/user-attachments/assets/39874b4b-2c5c-49a9-89c1-95e88999061e)

You will also see this window on the right, which shows the Arduino board:

![image](https://github.com/user-attachments/assets/e5f25645-23ad-4c9a-9b29-ae6c9ba321dc)

However, it says "Arduino1, Searching board...", its trying to connect to your Arduino:

![image](https://github.com/user-attachments/assets/c3f56c1c-35e0-46e1-baf4-1e87c25c48f6)

So let us connect it:

![image](https://github.com/user-attachments/assets/be9931e3-fd5f-4f95-b02f-f4dd73535e95)

You should see some flashing lights on your Arduino board, and now in Scratch you should see:

![image](https://github.com/user-attachments/assets/b3e47a4a-5d8f-4df0-97fa-cf13e7ec2ecc)

What is important to see is all those text fields have numbers changing all the time and it says "port: COM10" it may be
a different on you laptop like "port: COM5" or "port: COM3", this just tells us that Scratch is now connected to your Arduino!

![image](https://github.com/user-attachments/assets/37ed8646-f4e2-43af-9a08-0e022bfe8680)

Now you should all be quite familiar with Scratch, so now create the following:

![image](https://github.com/user-attachments/assets/fe5c658b-bbfa-471d-a2b0-417f89abc2c5)

Then run it:

![image](https://github.com/user-attachments/assets/05fcd5a0-f2bf-4784-96b0-665496b59642)

You should have seen that on your board, one of the LED lights is flashing on and off.

Modify the "wait" time

# Motor Control

Now let us connect the two servo motors to the Arduino.

We have our Arm motor and Gripper motor.

Remember the wiring:

![image](https://github.com/user-attachments/assets/4cfe076d-804f-4059-a592-9aa57c52bd90)

Now your Arduino looks something like this:

![image](https://github.com/user-attachments/assets/bf9e9c18-5c88-49e5-b700-03d16c5f1ea1)

We need to power both servos with these pins:

![image](https://github.com/user-attachments/assets/7c2c3736-570d-4a81-ac6a-eddd5293a9e2)

And we will control the angle with these pins:

![image](https://github.com/user-attachments/assets/a936f64f-29ff-4c45-8ceb-c67b481986f6)

When we learnt about servo motors we saw they require a DC voltage of:

![image](https://github.com/user-attachments/assets/ebfbe71d-ed02-49ad-a0ca-9fe64327f1b8)

However, we only have one 5V voltage pin that can supply that voltage range, yet we have two motors :( 

However, we can also use the 3.3V voltage pin, it is not ideal but it will still work :)

So let us start with Gripper motor. 

Using the male to male jumper wires:

- Connect the 3.3V pin from your Arduino to the red connector on your Gripper motor
- Connect a GND (ground) pin from your Arduino to the brown connector on your Gripper motor
- Connect pin 4 from your Arduino to the orange connector on your Gripper motor

![image](https://github.com/user-attachments/assets/d8225372-5a0c-4135-bc23-c2a3e141e559)

Next let us do the Arm motor. 

Using the male to male wires:

- Connect the 5V pin from your Arduino to the red connector on your Arm motor
- Connect a GND (ground) pin from your Arduino to the brown connector on your Arm motor
- Connect pin 8 from your Arduino to the orange connector on your Arm motor

So you should end up with the following:

![image](https://github.com/user-attachments/assets/1b4f1f19-2800-451a-a600-56ece2b5b0c0)

Why do you think we chose 5V for the Arm motor?

## Scratch Code

Now that you have connected your motors let us test them out.

### Motor Control
Create the following Scratch code blocks:

![image](https://github.com/user-attachments/assets/ff34b113-232c-4fa8-be66-d9eda507e772)

What does it do?

Change the motor value from "4" to "8" to control the other motor.

Make sure you have tested both of your motors before going on to the next section.

### Angle Control

Next, create a new project but now use this motor block:

![image](https://github.com/user-attachments/assets/3fd859a9-08c6-4b27-938b-1b366f97b870)

Change the values to see the angle of the servo change.

Make sure you have tested both of your motors.

# Next Lesson

If you have reached this point well done. Now we will put everything together that we have learnt and build our Robotic Arm!

Go to this page: https://github.com/ChpcTraining/dsi_coding_school/blob/dev/robotics/robotic_arm_project.md
