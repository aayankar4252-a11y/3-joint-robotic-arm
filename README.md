
# 3-Joint Robotic Arm

BlueStamp Engineering student portfolio

---

## Project Description

This project is a three-joint robotic arm controlled by an Arduino Nano. The arm uses multiple servo motors to create movement across three joints and a claw for gripping objects. User command is easily provided through a joystick controller, allowing the arm to move in multiple directions and manipulate small objects. Through this project, I am developing skills in electronics, programming, robotics, and mechanical design while exploring my overall interest in aerospace engineering.



| Aayan Kar | Waubonsie Valley High School | Aerospace Engineering | 10th Grade |

## **Milestone 1: Complete First 5 lessons on the GitHub guide**

What I Accomplished:

For this project, I will be building a three-joint robotic arm controlled by an Arduino Nano using servo motors and a joystick input system. For my first milestone, I completed the first five lessons from the Cokoino robotic arm guide. These lessons introduced me to the Arduino Nano, Arduino IDE, Nano Shield, joystick module, servo motors, and buzzer system that will be used throughout the project.

I successfully installed and configured the Arduino IDE, uploaded programs to the Arduino Nano, and learned how code can be transferred from a computer to a microcontroller. I also tested the Nano Shield and verified that all hardware connections were functioning properly.

<img width="1512" height="911" alt="Screenshot 2026-06-12 at 1 51 02 PM" src="https://github.com/user-attachments/assets/6f0e85c0-d162-4e5a-9061-42edf887e65e" />


Next, I tested the joystick module and observed how analog inputs are converted into numerical values that can be used to control movement. Finally, I programmed and tested the servo motors, learning how PWM signals can precisely control motor position and movement.

Challenges & Takeaways:

One challenge I had involved the buzzer in Lesson 3. The original code caused the buzzer to continue sounding indefinitely after activation. Rather than leaving the behavior unchanged, I analyzed the code and modified it by implementing a three-second timer that automatically turns the buzzer off.

<img width="1512" height="734" alt="Screenshot 2026-06-14 at 2 26 50 PM" src="https://github.com/user-attachments/assets/f8e1884e-f72e-40f7-888c-8b11e0044497" />


This was my first experience making changes beyond the provided instructions. Through this process, I learned how to troubleshoot Arduino programs, understand timing functions, and test modifications until the system behaved as intended.

This milestone gave me a strong foundation in Arduino programming, hardware integration, and engineering problem-solving, which will be essential as I begin assembling and controlling the robotic arm in the next phase of the project.


### Milestone 1 Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rx8uqX22Ve4?si=-P2WHc67zuXJRaa0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



## **Milestone 2 (Final Milestone): Build the Project**

What I Accomplished:

The goal of this milestone was to assemble the robotic arm by following Lesson 6 of the Cokoino guide. During this phase, I transformed the individual components that I tested in Milestone 1 into a complete robotic system.

Before beginning assembly, I calibrated each servo motor to a 90-degree position. This ensured that the servos would be properly aligned when installed into the robotic arm and helped prevent positioning errors during future operation.

<p align="center">
  <img alt="calibrated servos" src="https://github.com/user-attachments/assets/631ea719-b286-4922-9640-360f25a7a6b6" width="500">
</p>

After calibrating the servos, I assembled the robotic arm frame using the acrylic components and hardware provided in the kit. I carefully followed the guide to ensure that each part was installed in the correct orientation.

<p align="center">
  <img alt="assembled acrylic frame" src="https://github.com/user-attachments/assets/6b4a1aff-f73b-4650-926e-db7e6f21e7b9" width="500">
</p>


Once the frame was assembled, I mounted the servo motors into the arm's joints and connected the necessary electronic components. This allowed me to better understand how the mechanical structure and electrical systems work together to create movement.

<p align="center">
  <img alt="finished assembly" src="https://github.com/user-attachments/assets/112b4e4c-3f59-407e-8395-f6caf0b60b8c" width="500">
</p>


By the end of the milestone, I had successfully assembled the robotic arm and verified that all major components were securely installed and connected.

Challenges & Takeaways:

One challenge during assembly was ensuring that every servo and structural component was installed in the correct position. Since the arm contains multiple moving joints, even a small alignment error could affect performance later when programming movement.

To avoid mistakes, I frequently compared my progress to the guide's reference images and double-checked the orientation of each component before moving on to the next step.

This milestone taught me the importance of precision, patience, and attention to detail when assembling engineering systems. It also gave me a better understanding of how mechanical and electrical components interact within a robotic platform.

## System Schematic

As part of this project, I reviewed the robotic arm's schematic to better understand how the electrical components are connected. The schematic illustrates the relationships between the Arduino Nano, Nano Shield, servo motors, joystick module, and other components used throughout the system.

<p align="center">
  <img alt="wiring diagram image" src="https://github.com/user-attachments/assets/6760bd73-26ab-4ce6-a2f8-93404ebb2a6d" width="550" style="height:auto;">
</p>


Studying the schematic helped me visualize how signals and power flow through the robotic arm. It also gave me a clearer understanding of how the hardware components interact and provided a useful reference for troubleshooting and future modifications.


### Milestone 2 Video

<iframe width="560" height="315" src="[https://www.youtube.com/embed/Rx8uqX22Ve4?si=-P2WHc67zuXJRaa0](https://youtu.be/ejYQdZHItFI?si=N6FjHepKSyoCPwlF
)" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Bill of Materials

| Part | Notes | Price | Link |
|------|------|-------|------|
| Arduino Nano | Main microcontroller used to run the program | $10 | [Arduino Nano](https://shillehtek.com/products/arduino-nano-v3-0-atmega328p-16mhz-ch340c-type-c?variant=52246904144159&country=US&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOorXKWhQj8I3Qxv0_pan9y7JW7tQgSzN9K8mGpmOyuQB5X9KTMBzPco&com_cvv=8fb3d522dc163aeadb66e08cd7450cbbdddc64c6cf2e8891f6d48747c6d56d2c) |
| Nano Shield | Simplifies wiring between components and Arduino | $8 | [Nano Shield](https://uk-m.banggood.com/Multi-Function-Funduino-Nano-Shield-Nano-Sensor-Expansion-Board-Geekcreit-for-Arduino-products-that-work-with-official-Arduino-boards-p-91852.html) |
| Servo Motors (x4) | Controls movement of robotic arm joints and claw | $3–5 each | [Servo Motors](https://andymark.com/products/micro-servo-sg90?variant=44493483868332&country=US&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOop7tChkot3zcWA9CmaImRMLH_64i728dMXJGg0aR0aXoZ5CgX_y4OA&com_cvv=8fb3d522dc163aeadb66e08cd7450cbbdddc64c6cf2e8891f6d48747c6d56d2c) |
| Joystick Module | Provides user control input for the robotic arm | $5 | [Joystick Module](https://www.mouser.com/ProductDetail/SparkFun/COM-09032?qs=WyAARYrbSnb9u7eU4VaEfQ%3D%3D&mgh=1&srsltid=AfmBOooB69YoSCIj-o6Q0uBVCrOg8f4FYRyoVs2FHtc5AQcf_zPsOB820RM) |
| Acrylic Robotic Arm Kit | Mechanical structure of the robot | $25–40 | [Arm kit](https://www.walmart.com/ip/ZPAQI-Robot-Claw-Kit-Acrylic-for-Arduino-Study-Set-Easy-to-Use-Mechanical-Arm/1350797290?wmlspartner=wlpa&selectedSellerId=101661630) |
| Jumper Wires | Used for electrical connections between components | $5 | [Wires](https://www.microcenter.com/product/613879/Dupont_Jumper_Wire_20cm_-_3_Pack) |
| USB Cable | Used to upload code to Arduino Nano | $3 | [USB cable](https://www.cablewholesale.com/products/usb-firewire/usb-2.0-cables/product-10u2-03101bk.php?srsltid=AfmBOorDXswFUQfC9lH_obOL7SdMKPPSuf39GpkAmO86tePymTtS3lTPkXY) |
| 9V Alkaline Battery| Powers the system (USB or external battery) | $5–10 | [9V Alkaline Battery](https://www.amazon.com/Amazon-Basics-Performance-All-Purpose-Batteries/dp/B0774D64LT/ref=sr_1_5?c=ts&dib=eyJ2IjoiMSJ9.jrVCSONhihG2h1VpU3guB2TAgauTu0L4WS3THT0lt4DhObJteQ8Pu_msdbGnkX4-DvaGEI2taMWMBdRdPqW8XujFcNojVqwqnS9f5EGbzwAhDK_vpnxzLSIsIWQR61uYXYuFJgSa_afKwV2gFZmiRBTpdsTVLND5JnwwNlrwDXdZxJ3bCbq-4kwa2Rcj2ktk__fCgGUHabrwRxa6oOQKBSCysk0GE85-mJ7VPCiE2_NLR9MSVzVUo7FPNezlAuJgshR99AncF8Q9DmA0zjDsNu1Yrxhzp7VJZL1LrlbeXeg.cQiJbOjAXQm2NGrbL7SQMWi0crG-6jv9-AhRFAgpcVA&dib_tag=se&keywords=9V%2BBatteries&qid=1782147937&rdc=1&s=hpc&sr=1-5&ts_id=389576011&th=1) |

## Final Project Reflection

Through this project, I gained hands-on experience with Arduino programming, servo motor control, circuit wiring, mechanical assembly, and robotics. One of the most valuable lessons was learning how software and hardware work together to create a functional robotic system.

I also developed problem-solving skills by troubleshooting issues such as the buzzer continuously sounding and modifying the code so that it automatically stopped after three seconds. This experience showed me that engineering often involves identifying problems, testing solutions, and making improvements beyond the original design.

Reviewing the robotic arm schematic also helped me better understand how the Arduino Nano, Nano Shield, servo motors, and joystick module interact within the system. This gave me a clearer understanding of how signals and power are distributed throughout the robotic arm.

Overall, this project strengthened my interest in robotics and aerospace engineering while providing practical experience with both mechanical and electrical systems. It gave me valuable experience in programming, troubleshooting, assembly, and understanding how multiple engineering disciplines come together to create a working robotic system.
