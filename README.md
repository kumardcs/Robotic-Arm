# 4-DOF Bluetooth Controlled Robotic Arm 🤖

This project implements a **4 Degrees of Freedom (4-DOF) robotic arm** controlled wirelessly using **Bluetooth communication**. The system allows a user to control the movement of the robotic arm in real-time using a mobile device. The arm is powered by servo motors and controlled using an Arduino microcontroller.

## 📌 Project Overview

The robotic arm consists of four independently controlled joints that provide flexible movement for tasks such as **object manipulation, pick-and-place operations, and educational robotics experiments**. Communication between the user and the robotic arm is achieved through a Bluetooth module, enabling wireless control.

## ⚙️ Features

* Wireless control using Bluetooth
* Four degrees of freedom for flexible motion
* Real-time servo motor control
* Simple and low-cost hardware design
* Suitable for robotics learning and prototyping

## 🧩 System Components

* Arduino (Uno/Nano)
* HC-05 Bluetooth Module
* 4 Servo Motors
* Robotic Arm Mechanical Structure
* External Power Supply
* Mobile Bluetooth Controller Application

## 🏗️ Working Principle

The mobile application sends control commands via Bluetooth to the HC-05 module connected to the Arduino. The Arduino processes these commands and generates PWM signals to control the servo motors. Each servo motor corresponds to one joint of the robotic arm, allowing precise control of its movement.

## 🎯 Degrees of Freedom

1. Base rotation
2. Shoulder movement
3. Elbow movement
4. Gripper or wrist control

## 🚀 Applications

* Pick and place operations
* Robotics education
* Automation demonstrations
* Embedded systems learning
* Human-robot interaction experiments

## 🔧 Future Improvements

* Implement inverse kinematics for precise positioning
* Add computer vision for object detection
* Improve trajectory planning and motion control
* Develop a custom mobile control interface

## 📚 Learning Outcomes

This project demonstrates concepts from **robotics, embedded systems, wireless communication, and control systems**.

---

⭐ If you find this project useful, feel free to star the repository!
