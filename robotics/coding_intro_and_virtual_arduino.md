# What the "code" actually looks like

![image](https://github.com/user-attachments/assets/df7f1d4b-0ae1-487c-9bf8-badbe9acfc83)


| **Concept**             | **Scratch Equivalent**         | **Arduino Code**                        | **Explanation**                                                             |
|-------------------------|---------------------------------|------------------------------------------|-----------------------------------------------------------------------------|
| **Setup**               | "When green flag clicked" block | `void setup()`                           | Code that runs once at the start.                                           |
|                         |                                 | `pinMode(13, OUTPUT);`                   | Sets pin 13 as an output.                                                   |
| **Loop**                | "Forever" block                | `void loop()`                            | Code that runs continuously.                                                |
| **Turn LED On**         | "Digital 13 on" block      | `digitalWrite(13, HIGH);`                | Turns the LED on by setting pin 13 to HIGH.                                 |
| **Wait**                | "Wait 1 second" block           | `delay(1000);`                           | Pauses for 1 second (1000 milliseconds).                                    |
| **Turn LED Off**        | "Digital 13 off" block     | `digitalWrite(13, LOW);`                 | Turns the LED off by setting pin 13 to LOW.                                 |


```cpp

void setup() {
    // Set pin 13 as an output
    pinMode(13, OUTPUT);
}

void loop() {
    // Turn the LED on
    digitalWrite(13, HIGH);
    // Wait for 1 second
    delay(1000);
    // Turn the LED off
    digitalWrite(13, LOW);
    // Wait for 1 second
    delay(1000);
}
```

> Take note of the curly brackets `{ }` used with `void setup()` and `void loop()`, and the semi-colon `;` at the end of each line. They are necessary part of coding an Arduino.

# Introduction

Scratch is a powerful introduction to coding concepts, especially for young learners. It's a visual programming language designed to help students grasp the fundamentals of computational thinking, like loops, conditionals, and variables, without getting bogged down by the complexity of syntax. The blocks in Scratch represent code that students can drag, drop, and arrange to create interactive stories, animations, or games, making it very accessible and intuitive.

However, Scratch is not real-world coding in the sense that most professional programming environments rely on text-based languages like Python, Java, or JavaScript. These languages require a more detailed understanding of syntax and structure, as well as debugging skills, which are critical in professional coding. In the industry, developers write code in text editors or Integrated Development Environments (IDEs) to create software that powers everything from websites and apps to scientific computing and artificial intelligence systems.

# Why Scratch is Important

For high school students, Scratch is an excellent tool to introduce logic, creativity, and problem-solving in coding without overwhelming them. The visual nature of Scratch lowers the barrier to entry and allows students to see immediate results of their work, which keeps them engaged. It teaches foundational concepts that are transferable to text-based languages. These include:

Control structures: Understanding loops, conditionals, and events, which are universal across most programming languages.
Debugging: Finding and fixing issues, a core skill in any form of coding.
Creative thinking: Designing and problem-solving through projects.

# Transitioning to Text-Based Coding

However, it is essential to communicate to students and teachers that Scratch is a starting point rather than an end goal. In the real world, text-based programming is the industry standard for developing applications, managing data, or building systems. When students transition from Scratch to languages like Python or Java, they encounter:

Syntax: Precise, rule-based structures. Text-based coding requires correct placement of semicolons, parentheses, and indents, which can be unforgiving.
Complexity: Text-based languages allow for more complex tasks, but they also demand understanding of error messages, functions, data types, and libraries.
Version control and collaboration: Professional coding often involves working on teams using tools like Git to manage changes across codebases—skills that are not emphasized in Scratch.

# Preparing Students for Industry

For teachers, it's vital to help students see that Scratch is just the beginning. Text-based programming is critical to many careers—ranging from software development to data science—and introducing students to it early gives them a better understanding of the broader coding landscape. Transitioning from Scratch to text-based coding is like moving from building blocks to blueprints—both are essential but serve different stages in a student's development.

Encourage students to see coding as a journey. Once they grasp the concepts in Scratch, they should be challenged with text-based coding platforms like Python, where they can apply the same logic to more complex, real-world problems.

# Coding in the Arduino IDE

In windows search for Arduino IDE and open it:

![image](https://github.com/user-attachments/assets/db0f756d-ab72-4817-aa2a-5a07649553f7)

You will see:

![image](https://github.com/user-attachments/assets/1f4efcd3-147c-4669-acec-ecd95c96a17d)

Now open an example piece of code, File -> Examples -> 01. Basics -> Blink 

![image](https://github.com/user-attachments/assets/50265988-270f-47ae-b2d8-3bd7a4089d0c)

And you will see:

![image](https://github.com/user-attachments/assets/3cf09ae8-4c89-4477-9f10-087f1431bbbd)

This is the same as:

![image](https://github.com/user-attachments/assets/55e599e6-0104-4535-aec6-4ee5746d7657)

So this is just a list of instructions that your computer will interpret. Follow the arrows:

![image](https://github.com/user-attachments/assets/648f2aed-4e1a-43d6-9818-8bf12133d03b)

Then the `void loop() {` section happens forever, just like the `forever` control we used in Scratch.

Take note of the how the instructions are ordered, the syntax, brackets etc. This all forms part of programming.

# Online Scratch with Arduino Simulation

[https://en.vittascience.com/code](https://en.vittascience.com/code)

![image](https://github.com/user-attachments/assets/e6a9d716-588d-4511-8ec7-b6209d9c50ab)

[https://en.vittascience.com/arduino/](https://en.vittascience.com/arduino/)

![image](https://github.com/user-attachments/assets/62db4ca4-865b-435a-97a0-5e68cdf4e603)

![image](https://github.com/user-attachments/assets/13f6da4f-0092-4b25-95c6-555bac7337f8)

# Online Arduino Simulation

https://wokwi.com/projects/new/arduino-uno

![image](https://github.com/user-attachments/assets/c9f2875e-6232-47b5-a364-5cde7b10d9bd)

![image](https://github.com/user-attachments/assets/393d5f43-d7ed-4f9f-8004-9a3ef66b9cf2)

![image](https://github.com/user-attachments/assets/f31715f1-f221-4cb3-89c2-5f80f9c4a6a9)

![image](https://github.com/user-attachments/assets/cc2493c3-293d-48d6-b74f-03b0a20f297d)

![image](https://github.com/user-attachments/assets/4dcbbeab-40f1-4523-b1c2-299b509b437d)

# Arduino Buzzer Example

Go to this link to see a buzzer project with an Arduino:

[https://wokwi.com/projects/334566563776561746](https://wokwi.com/projects/334566563776561746)

![image](https://github.com/user-attachments/assets/6d12e336-f75e-46b4-8a66-0c97a79a8903)

# Arduino Push Button Example

![image](https://github.com/user-attachments/assets/9fe5f2bf-8501-4dd9-8c74-09c78da8669d)


# Arduino Many Push Buttons

[https://wokwi.com/projects/377569194875794433](https://wokwi.com/projects/377569194875794433)

![image](https://github.com/user-attachments/assets/cd83d211-510e-4a1a-98d1-0f20c8d0194b)

# Arduino Piano

[https://wokwi.com/projects/291958456169005577](https://wokwi.com/projects/291958456169005577)

![image](https://github.com/user-attachments/assets/f1289374-ceac-4735-8680-21c8c90fe20d)

# Another Arduino Virtual Environment

[https://cloud.arduino.cc/?gad_source=1](https://cloud.arduino.cc/?gad_source=1)

![image](https://github.com/user-attachments/assets/21bf67ec-7c06-4adb-94ee-febc9aeb9712)




