# Level 2


## 1. **UAV Assembly & Flight Controller Configuration:**

- **Objective:** To collaboratively assemble and configure a fully functional quadcopter with GPS, receiver, and flight controller integration.
- **Task:**
  - Use the components finalized in Level 1, Task 3 and get the list approved by the coordinators.
  - Assemble a complete quadcopter as a group, all the batch students should actively take part in the drone building.
  - Bind the drone to the Radiomaster RP1 receiver and control it using the TX16S transmitter.
  - Interface the Mission Planner software with the flight controller using a USB connection.
  - Connect a GPS module to the flight controller and configure it.
  - Calibrate all sensors (accelerometer, compass) and radio inputs.
    *(OPTIONAL)*
    - Integrate a Lidar or Ultrasonic Sensor with the flight controller.
    - Write and test a basic obstacle detection script that alters the drone's flight path based on sensor input.
- **Outcome:** Build, calibrate the drone & prepare a detailed project report in word doc. The report should include the names of all team members, the specific work assigned to each member, and a comprehensive explanation of all technical aspects of the drone from start to finish. Post the report on GitHub (.PDF),  ensure the GitHub repository link is posted on the MARVEL website under the corresponding task.

*Resources:*
1. [ArduPilot tuning Guide P1](https://www.youtube.com/watch?v=m458L_0-0EY&t=956s)
2. [ArduPilot tuning Guide P2](https://www.youtube.com/watch?t=1644&v=R3WqLWLy4Cw)

![](https://github.com/Asshrayyyy/MARVEL-Aviation-/blob/main/DRONEAMS.jpg?raw=true)

---

## 2. **Autonomous Flight Planning & Execution:**

- **Objective:** To understand and practice autonomous flight mission planning using Mission Planner and the ArduPilot simulator.
- **Task:**
  - Learn about the Heads Up Display (HUD) available in the Mission Planner.
  - Using the built-in Ardupilot simulator (SITL), plan and execute a geofence around UVCE and test a small autonomous mission.
    *(OPTIONAL)*
    Learn about automated aerial surveying, different modes of surveys available in Mission Planner, and perform a automated aerial survey of UVCE.
    Execute the flight and analyze logs for accuracy.
- **Outcome:** Perform the above tasks and write a detailed report. Video of the automated flight should be included in the report.

*Resources:*
1. [SITL Setup](https://www.youtube.com/watch?v=gnSbaGDzrHE)
2. [Geofencing & Surveying](https://www.youtube.com/watch?v=rui2Trps2yc&list=PL41SZdWB8u1AxPLbf2VC0tkDq0HnbVPKz&index=2)

![](https://github.com/Asshrayyyy/MARVEL-Aviation-/blob/main/11111111111.png?raw=true)

---

## 3. **Introduction to MATLAB:**

- **Objective:** To gain foundational knowledge of MATLAB and Simulink.
- **Task:**
  - Complete the MATLAB Onramp course.
  - Complete the Simulink Onramp course.
  - Download and upload both certificates as proof of completion.
- **Outcome:** Perform the above tasks and write a detailed report which should include the certificates of completion.

*Resources:*
1. [Course Link](https://matlabacademy.mathworks.com/?page=1&sort=featured&s_tid=user_nav_learning)

---

## 4. **Advanced PID Tuning:**

- **Objective:** To develop a strong understanding of PID controllers and their application in UAV stability and autonomous control systems.
- **Task:**
  - Watch at least the first 5 videos from the provided PID resource playlist, write a detailed report about the learnings.
  - Connect a UAV to Mission Planner and observe the default PID values for roll, pitch, and yaw.
  - Build a self-balancing car that operates using PID control principles.
  - Experiment by adjusting PID parameters (P, I, and D) one at a time and observe the effect on system stability.
- **Outcome:** Perform the above tasks and write a detailed report.

*Resources:*
1. [Recall PID with the help of Chat GPT analogy](https://chatgpt.com/share/680dfe75-0d78-800a-af8a-337b6a9d852a)
2. [PID in depth ~Watch at least first 5 videos](https://www.youtube.com/watch?v=wkfEZmsQqiA&list=PLn8PRpmsu08pQBgjxYFXSsODEF3Jqmm-y&index=2)
3. [Initial PID setup & tuning in mission planner](https://www.youtube.com/watch?v=R3WqLWLy4Cw&t=2411s)
4. [Self Balancing Car](https://www.youtube.com/watch?v=pbJbpHjC3v0)

---

## 5. **Rules in the Rule Book Written by Blood:**

- **Objective:** To explore the methodology behind air crash investigations and learn how aviation safety evolves from past incidents.
- **Task:**
  - Take an example of a previous Air Crash  from [Wyngx](https://www.youtube.com/@_WyngX/videos) or any other source of your choice. 
  - Write a detailed report of the air crash investigation, the report should include:
    - Details of the flight, place, time, pilot details and an introductory paragraph about the accident which occurred /was about to occur including the losses occurred.
    - Explain in brief about the aircraft.
    - Using the Swiss Cheese Model analyze the key contributing factors (technical, human, environmental etc.) and also explain how each of these factors (layers of the Swiss Cheese) accelerated the accident when aligned together.
    - State the various theories and assumptions which took place during the investigation and also mention the reasons which led to the elimination/confirmation of these theories.
    - Reflect on what lessons were learned and how aviation standards changed post-accident.
- **Outcome:** Perform the above tasks and write a detailed report in Word Doc, post it on GitHub (.PDF),  ensure the GitHub repository link is posted on the MARVEL website under the corresponding task.

*Resources:*
1. [Wyngx](https://www.youtube.com/@_WyngX/videos) or any other source of your choice.

![](https://github.com/Asshrayyyy/MARVEL-Aviation-/blob/main/rules%20in%20the%20rulebook%20written%20by%20blood.png?raw=true)

---

## 6. **Flight Data Logging & Analysis:**

- **Objective:** To explore the methodology behind air crash investigations and learn how aviation safety evolves from past incidents.
- **Task:**
  - Extract log files from a Pixhawk/APM flight controller.
  - Analyze flight stability, GPS accuracy, battery performance using Mission Planner.
  - Generate graphs for:
    - Altitude vs time.
    - Throttle & Battery vs time consumption.
    - Velocity vs time
    - Suggest improvements based on data trends.
  - Also convert the `.bin` log files to `kml+gpx` formats and upload the obtained `kmz` files to Google Earth to view the 3D path followed by the drone. Try to simulate the same flight path on Google Earth using the kmz files, state the problems faced if any.
- **Outcome:** Analyze all the 3 LOG files given and write a detailed report.

*Resources:*
1. [Retrieval of LOG files](https://www.youtube.com/watch?v=xhBd9KSAfzg)
2. [Link to LOG files](https://github.com/Asshray-Sudhakar/MARVEL-Aviation-Students-Resources/tree/main/LOG%20Files)

![](https://github.com/Asshrayyyy/MARVEL-Aviation-/blob/main/black-box-update.jpg?raw=true)

---

## 7. **Introduction to ROS 2 for UAVs:**

- **Objective:** To get started with the Robot Operating System (ROS) 2 ecosystem and understand its application in UAV communication through node-based architecture.
- **Task:**
  - Install and set up Ubuntu 22.04 and ROS 2 Humble Hawksbill.
  - Learn the basics of:
    - Nodes
    - Topics
    - Publishers
    - Subscribers
  - Create a Publisher Node that sends fake drone altitude data
  - Create a Subscriber Node that reads and displays this altitude data in real-time
    *(OPTIONAL)*
    - Modify the Publisher node to also publish Battery Level data along with the altitude.
- **Outcome:** Perform the above tasks and document steps clearly with screenshots and code snippets.

*Resources:*
1. [Ubuntu 22.04 Setup](https://www.youtube.com/watch?v=hYaCCpvjsEY)
2. [Basics of ROS 2 Terms](https://www.youtube.com/shorts/hTHZC-x91ic)
3. [Multiple terminals using terminator](https://www.youtube.com/watch?v=cRS8q6vDI8Y&t=12s)
4. [ROS 2 Setup & Task Tutorial](https://www.youtube.com/watch?v=0aPbWsyENA8&list=PLLSegLrePWgJudpPUof4-nVFHGkB62Izy&index=2)

![](https://github.com/Asshrayyyy/MARVEL-Aviation-/blob/main/ROS%202.png?raw=true)

--- 
### All The Best!!

---
