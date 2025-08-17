# Level 0

## Generic Tasks
## TASK 1: 3D Printing

Understand the working of a 3D printer, check out the online resources. Understand what's an
STL file, and then learn to slice it (using ultimaker or creality slicer).Go through the SOP'S regarding the 3d printer. Learn about bed
temperature, infill density and other printer settings. Finally get an STL file from the internet, and
slice it and put it for print.

Resources:

● [Introduction to 3d printer](https://www.youtube.com/watch?v=kM5zRO3n9-Y)

● [PLA settings](https://standardprintco.com/read/pla-filament-printing-guide-how-to-succeed-printing-pla-and-troubleshooting-common-problems-step-by-step)

● [Types of 3D printing](https://formlabs.com/asia/blog/fdm-vs-sla-vs-sls-how-to-choose-the-right-3d-printing-technology/)

(Note this task is to be done under coordinator supervision.)
![3dprinter](https://gist.github.com/user-attachments/assets/6339d1a8-82d4-4631-8fd6-af7d77de983f)

### Task 2: API

Learn what an API is and how it works through [this video](https://www.youtube.com/watch?v=s7wmiS2mSXY). Using any API of your choice, build a user interface (web app, mobile app, etc.) to make calls and display information. An example weather app using the Open Weather API is provided below.

**Resources:**
- [Example Weather App](https://www.youtube.com/watch?v=HAVPicZJ9ik&feature=youtu.be)

---

### Task 3: Working with GitHub

Familiarize yourself with GitHub integrated workflows such as GitHub Actions, Issues, and pull requests. Visit the provided git repository and perform the tasks stated in the README file.

**Check this link for more info:**
- [GitHub Task Repository](https://github.com/UVCE-Marvel/git-task)

---

### Task 4: Command Line on Ubuntu

Get familiar with the command line on Ubuntu by completing the following subtasks:
- Create a folder named `test`.
- `cd` into that folder.
- Create a blank file without using any text editor.
- List the files in that folder.
- Create 2600 folders in this folder, each named with a format like M90 or B56.
- Concatenate two text files containing random text and display them on the terminal.

**Resources:**
- [Command Line for Beginners](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview)

---
## Task 5 : *Build Your Own Brain* -Linear Regression from Scratch

Dive into the core of machine learning by implementing **Linear Regression from scratch** using , and compare its performance with the **scikit-learn implementation**. Use the **California Housing dataset** to evaluate your model on real-world data.
<br>
### Your Task:
- Implement linear regression manually (without using ML libraries for training).
- Understand and apply gradient descent to minimize error.
- Compare your custom model’s performance against `sklearn.linear_model.LinearRegression` .
- You should analyze results by:
	 * Graph showing line of best fit and the datapoints.
	 * Performance metrics: MSE, MAE, R² for both custom and scikit-learn models.
	 * Brief comparison between two models.
<br>
[Download Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
### Learn Linear Regression:
1. Understanding :
     - [Linear Regression](https://www.geeksforgeeks.org/ml-linear-regression/)
     -  [Gradient Descent](https://youtu.be/sDv4f4s2SB8?feature=shared)

2. Coding the linear regression algorithm from scratch:
- https://towardsdatascience.com/coding-linear-regression-from-scratch-c42ec079902
- https://www.askpython.com/python/examples/linear-regression-from-scratch
- https://medium.com/data-science/linear-regression-using-gradient-descent-97a6c8700931

### Expected Outcomes:

- Grasp how gradient descent optimizes weights in linear regression.
- Understand the importance of feature scaling.
- Know how to evaluate regression models using standard metrics.
- Be able to appreciate the convenience and performance of inbuilt ML libraries.

### Precautions:

- Always normalize or standardize features before training your scratch model, especially if you’re using gradient descent.
- Be cautious with your **learning rate** , too small and the model is slow, too large and it may diverge.
- Initialize weights and bias properly ( small random values or zeros).

## Task 6 : The Matrix Puzzle — Decode with NumPy & Reveal the Image

Get hands-on with NumPy and Matplotlib by solving a visual puzzle. You’ll be given a scrambled matrix, and your mission is to decode it into a hidden image using NumPy operations and visualization techniques.

### Your Task:
* Download the scrambled matrix from the link provided.
* Use your knowledge of NumPy to manipulate, reshape, and reorient the matrix.
* Reveal the secret image by plotting it using `matplotlib.pyplot.imshow()` .
* Scrambled Matrix: [Download Here](https://drive.google.com/file/d/1YDwFs-nnAwevVfPdvcjLMhhNA3gEnUxO/view?usp=drive_link)
* NumPy Learning Doc: [Explore Here](https://colab.research.google.com/drive/1WHwChJ-8PO8sPuY0NM-5UpHP98Fjj5bA?usp=sharing)

### Learn NUMPY:

* https://youtu.be/QUT1VHiLmmI?feature=shared
* https://www.w3schools.com/python/numpy/default.asp
* https://www.datacamp.com/tutorial/python-numpy-tutorial
* [Official Documentation](https://numpy.org/doc/2.2/)

### Learn Matplotlib:

* [Official Documentation](https://matplotlib.org/stable/index.html)
* https://www.datacamp.com/tutorial/matplotlib-tutorial-python
* https://youtu.be/3Xc3CA655Y4?feature=shared

Decode the Matrix using these clues and Visualize it :
* `"Try reshaping the encoded array into a square—how many elements are there?"`
* `"The structure may be upright, but the data might be sideways. Look at its orientation."`
* `"Sometimes the end is actually the beginning."`

### Expected Outcomes:
- Gain confidence with NumPy operations like reshaping, slicing, flipping, and transposing.
- Learn to visualize 2D arrays using Matplotlib.
- Sharpen your debugging and puzzle-solving skills in a fun context.

### Precautions:
- Check the shape of the array before applying `imshow()` - wrong dimensions will throw errors.
- Ensure that your reshaped matrix has the correct number of elements (it's likely a square!).


---

### Task 7: Create a Portfolio Webpage

Create a website to showcase your portfolio, including information about yourself, interests, projects, and social media profiles. Ensure the site is responsive and pushed to a git repository. Use any CSS framework of your choice.

---

### Task 8: Writing Resource Article Using Markdown

Markdown is a markup language used to format plain text. Write a technical resource article on a particular use case or application of UAVs. This article will help you gain technical knowledge and create a framework for future projects.

**[Link](https://hub.uvcemarvel.in/article/52f92f36-fb8a-45da-8f28-686bf4efefff)**

---

### Task 9: Tinkercad

Create a Tinkercad account and familiarize yourself with the application. Simulate a simple circuit using an ultrasonic sensor to estimate the distance between an obstacle and the sensor, and display the results on the serial monitor. Create a radar system using an ultrasonic sensor and servo motor to detect objects within a certain range.

**Resource:**
- [Tinkercad Radar System Tutorial](https://youtu.be/NwmcNCvUcDc?si=x2LAYMFiqs1SzLfI)

**Task Outcomes:**
- Introduction to Tinkercad.
- Understanding ultrasonic sensors and servo motors.
- Basics of radar technology.

---

### Task 10: Speed Control of DC Motor

Explore techniques for controlling DC motors using the L298N motor driver and Arduino board. Control the speed of a 5V DC motor with an Arduino UNO and H-Bridge L298N motor driver. Simulate this on Tinkercad and then perform it on hardware. Record videos of the process.

**Reference:**
- [Arduino DC Motor Control Tutorial](https://howtomechatronics.com/tutorials/arduino/arduino-dc-motor-control-tutorial-l298n-pwm-h-bridge/)

---

### Task 11: LED Toggle Using ESP32

Learn how to use an ESP32 to create a standalone web server that controls an LED connected to the ESP32 GPIOs. Use the Arduino IDE to code and upload the program to the ESP32.

**Reference:**
- [Control LEDs Using ESP32 Web Server](https://microdigisoft.com/control-leds-using-esp32-web-server-in-arduino-ide/)

---

### Task 12: Soldering Prerequisites

Learn about soldering equipment such as solder, soldering iron, soldering wick, and flux. Perform basic soldering on a perf board, such as a simple LED circuit, under the supervision of a coordinator.

**Reference:**
- [How to Solder](https://www.makerspaces.com/how-to-solder/)

---

### Task 13: Design a 555 Astable Multivibrator

Design a 555 astable multivibrator with a duty cycle of 60%. Assemble the circuit on a breadboard and observe the output on a Digital Storage Oscilloscope (DSO).

**Resource:**
- [555 Oscillator Circuit](https://www.electronics-tutorials.ws/waveforms/555_oscillator.html)

---

### Task 14: Karnaugh Maps and Deriving the Logic Circuit

For 4 cases involving door lock/open and key pressed/not pressed, determine the Karnaugh map and create a burglar alarm using simple logic circuits. Use push buttons for the door and key, and design the circuit based on the K-map.

---

### Task 15: Active Participation

Participate in any technical event, inter-college or intra-college, and submit the issued certificate of participation. Enroll in and complete a MOOC course.

---

### Task 16: Datasheets Report Writing

Study the datasheet of either the MQ135 gas sensor or the L293D motor driver and write a report. For the L293D, include details about the ICs used, PWM, and H-bridge. For the MQ135, include calibrations for different gases and the Freundlich Absorption Theorem Graph.
## Task 17: Introduction to VR

Familiarise yourself with what Virtual Reality is. Make a detailed study about what's the difference between VR and AR. Mention about the trends in the space and technology stack being developed. Make about Indian companies in this space. Make the report with detail. Using generative AI to generate this study can lead to disqualification.

![vrlol](https://gist.github.com/user-attachments/assets/f9c1c57b-5861-4ffb-9c2b-31f01f184531)


## TASK 18: Sad servers - "Like LeetCode for Linux"
Sadservers is an excellent ground to test your Linux troubleshooting skills.  Here is a troubleshooting scenario: Command Line Murders. Troubleshoot and Make Sad Servers Happy!  
[Command line murder](https://sadservers.com/scenario/command-line-murders )  
[Linux commands]( https://www.hostinger.com/tutorials/linux-commands )    
[Linux commands]( https://github.com/vvvvvvss/learnLinux )   

## Task 19: Make a Web app
Using express create a resource library website where you can browse the resource articles, books etc which are available and also manage your account  
[Reference](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)

---

## Aviation Domain-Specific Tasks
---

## 1. **History of Aviation**

- **Objective:** To learn about the history of Aviation & Drones.
- **Task:**
  - Learn about the history of aviation and drones.
  - The resource video presents a concise animated timeline of aviation history. It covers:
    - Early myths and human attempts at flight (e.g., Icarus)
    - The Wright brothers’ first powered flight in 1903
    - Developments during World Wars I & II, including fighter aircraft
    - The invention of jet engines and the rise of commercial airliners
    - The introduction of supersonic flight (e.g., Concorde)
    - The emergence of drones (UAVs) in modern times
- **Outcome:** Show your learning in the form of a timeline/flowchart.
- **Platform:** [Notion](https://www.notion.com/) for creating the flowchart & [Draw.io](https://app.diagrams.net/) for editing it.

*Resources:*
1. [Video Resource](https://www.youtube.com/watch?v=mioZ3CQKoEg)
2. [Resource Article](https://www.spartan.edu/news/history-of-aviation/)

---

## 2. **Introduction to Flight Simulators**

- **Objective:** To learn manual controls, stability handling, and motor mixing using a drone simulator.
- **Task:**
  - Learn about the different channels available in the RC and how to control or maneuver the drone.
  - Learn how each motor affects the roll, pitch, and yaw of the drone.
  - Learn how to connect and set up the TX16S RC to the application.
  - In the simulator fly the drone in Angle mode, follow a specified drone path as told by the coordinator.
- **Outcome:** Perform the above tasks and write a detailed report.
- **Platform:** [Real Drone Racing](https://www.realdronesimulator.com/downloads)
- **_Note:_**  You can use your own computer or the MARVEL systems but the TX16S MKII should be used only in the presence of aviation coordinators.

*Resources:*
1. [Right way to hold a Tx ](https://www.youtube.com/watch?v=zqQgW7S89-w)
2. [What are Channels in a Tx?](https://www.youtube.com/watch?v=htv90KHbJak)
3. [Understanding Roll, Pitch & Yaw](https://www.youtube.com/watch?v=nb74_jkr8u0)
4. [Control of Roll, Pitch & Yaw using a Tx](https://www.youtube.com/watch?v=uFui-0sTQD0)
5. [Understanding motor mixing algorithms in a drone](https://www.youtube.com/watch?v=hGcGPUqB67Q)

![](https://github.com/Asshray-Sudhakar/MARVEL-Aviation-Syllabus-Repo/blob/main/RDSLogo_420x200.png?raw=true)

--- 

## 3. **Flying the Airblock Drone**

- **Objective:** To learn about and operate the Airblock Drone available in the lab.
- **Task:**
  - Write a report about the drone which should include the name of the application used to fly the drone, type of motors used, material of the drone, propellers used, battery details etc.
  - Fly the drone in a certain specified path as told by the coordinator, record it and put it up on the report.
-  **Outcome:** Perform the above tasks and write a detailed report in the Blog Post section, provide link to your blog post in the main report.
- **Platform:** [MakeBlock App](https://play.google.com/store/apps/details?id=cc.makeblock.makeblock&pcampaignid=web_share)
- **_Note:_**  This task should be performed only in the presence of aviation coordinators.

*Resources:*
1. [App Guide](https://qiniu.makeblock.com/makeblock-download/AirblockAPP-EN.pdf)
2. [Technicalities of the Drone](https://www.robot-advance.com/EN/actualite-the-new-drone-of-makeblock-121.htm)

![](https://github.com/Asshray-Sudhakar/MARVEL-Aviation-Syllabus-Repo/blob/main/airblock%20drone%201.jpg?raw=true)

---

