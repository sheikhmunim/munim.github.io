# Projects

## 🚀 Tiago Robot: Dynamic Task Planning with NLP

Developing a hybrid system that allows the Tiago robot to dynamically adjust task execution based on natural language instructions, combining PDDL planning, ROSPlan, and low-level behavior trees.

---

## 📦 Autonomous Delivery Robot with Visual Servoing

As part of a group project, I worked on developing an autonomous indoor delivery robot using a ROSBot platform. The robot uses computer vision to detect ArUco markers, which act as pickup and delivery location indicators, and navigates through indoor spaces without relying on GPS.

My main contribution to the project was building the ArUco marker detection and localisation system. I implemented real-time marker detection using OpenCV, and designed a stable pose estimation pipeline that integrates with ROS2's TF2 framework for accurate global localisation. To make the system reliable, I addressed practical challenges such as time synchronisation issues, unstable Z-axis pose estimates, and TF transform errors, all of which are common in real-world robotics applications.

I also contributed to setting up Nav2, the robot's autonomous navigation stack. This included helping integrate the vision system with navigation and visual servoing, so the robot could approach the correct location and align precisely for pickup or delivery.

This project gave me hands-on experience with real-time perception, localisation, and autonomous navigation in ROS2, while also teaching me the importance of debugging and refining robotics systems under practical conditions.

Key Areas I Worked On:
• ArUco Marker Detection and Pose Estimation
• TF2-based Localisation Pipeline
• Real-Time ROS2 Integration
• Nav2 Setup and Visual Servoing Integration
• Debugging Transform and Time Synchronisation Challenges

[GitHub Repository](https://github.com/sheikhmunim/rosbot_delivery_system)

## 📺 Watch the system in Action

<iframe width="560" height="315" src="https://www.youtube.com/embed/_XUKwFcZk8w" frameborder="0" allowfullscreen></iframe>

---

## ROS2 Search & Navigation Challenge — Hazard Detection  
**Role:** Hazard Detection Developer (Group Project)  
**Framework:** ROS2 Autonomous Robot System  

Contributed to the development of an autonomous robot capable of exploring unknown environments, detecting hazards, and returning to the start position.

- Designed and implemented the Hazard Detection module using ROS2 and TF2.  
- Integrated camera-based object detection to identify and localize hazards in real-time.  
- Transformed hazard positions from the camera frame to the global map frame for accurate localization.  
- Published visual hazard markers for real-time RViz visualization and system status updates.  

**Tools & Technologies:** ROS2, Python, TF2, RViz, Computer Vision  

[GitHub Repository](https://github.com/sheikhmunim/Rosbot_SNC)
---

## Colon Cancer Image Classification

As part of a biomedical machine learning project, I developed a deep learning system for classifying colon cell histopathology images into cancerous vs. non-cancerous and cell type categories (fibroblast, inflammatory, epithelial, others). The project used a modified version of the CRCHistoPhenotypes dataset containing 27x27 RGB images from 99 patients.

I designed and trained convolutional neural networks (CNNs) with techniques such as L2 regularization, dropout, batch normalization, and focal loss to improve model robustness and handle class imbalance. The final model achieved 90% accuracy and 0.85 F1-score for cancer detection, and 81% accuracy and 0.67 macro F1-score for cell type classification.

Additionally, I explored semi-supervised learning by incorporating unlabeled data, providing practical insights into its benefits and limitations for real-world medical AI applications.

[GitHub Repository](https://github.com/sheikhmunim/cml_assignment2)

---

## LZV Cup Tournament Scheduling — ASP & Clingo

**Project Type:** AI Planning & Optimization  
**Tools Used:** Answer Set Programming (ASP), Clingo, Python  

### Overview
This project focused on generating fair and feasible match schedules for the **LZV Cup**, a non-professional indoor football league. The tournament follows a time-relaxed round-robin format with real-world constraints like team availability, rest periods, and fairness requirements.

### Approach
We modelled the scheduling problem using **Answer Set Programming (ASP)** — a declarative logic-based approach well-suited for complex constraint satisfaction tasks. The **Clingo** solver was used to compute valid schedules under these constraints.

To handle instance preparation, result processing, and validation, we developed a supporting Python pipeline.

### My Contributions
- Designed alternate ASP constraints to improve solution quality  
- Developed layered **heuristics** to guide the solver toward better schedules  
- Created a **Python validator** to check calendar correctness and compute penalties  
- Experimented with **multishot solving** to dynamically adjust weights during optimization  
- Analyzed solver configurations (heuristics, enumeration modes, deletion strategies)  

### Key Results
- Applied heuristics reduced total penalty from **2537 to 2485**, and solver runtime from **1.2s to 0.1s**  
- Final model produced competitive schedules comparable to published metaheuristic benchmarks  
- Validator ensured strict rule compliance and provided penalty-based quality metrics  

### Reflections
This project demonstrated how ASP, when combined with well-designed heuristics, can rival traditional optimization methods like Tabu Search. The experience deepened my understanding of constraint modeling, solver tuning, and hybrid AI system design.


---

## Formula Bharat — Formula 6 (Electronics Team Lead)  
*Vehicle Electronics | Quick Shifting | BSPD | Performance Optimization* 

I led the Electronics Team for our Formula 6 car, competing in the Formula Bharat student racing competition. My work focused on designing and developing reliable, efficient, and competition-compliant electronic systems to enhance the vehicle's performance and safety.

**Key Contributions:**  
- Designed a cost-effective and reliable Electrical Quick Shifting Mechanism to replace expensive commercial alternatives, allowing rapid gear shifts with minimal maintenance.  
- Developed a BSPD (Brake System Plausibility Device) circuit as per Formula Bharat 2020 regulations. This system prevents simultaneous braking and acceleration, ensuring vehicle shutdown in case of stuck throttle scenarios.  
- Used MATLAB to analyze and optimize vehicle performance parameters, identifying inefficiencies and implementing improvements.  
- Upgraded the dashboard with an LED strip indicator, providing the driver with clear real-time feedback during operation.  

**Technologies & Tools:**  
Embedded Systems, Circuit Design, MATLAB, Vehicle Safety Systems, Performance Tuning  

This project allowed me to apply practical electronics design and problem-solving skills in a competitive motorsport environment.

## 📺 Watch the project in Action

<iframe width="560" height="315" src="https://www.youtube.com/embed/WJLxU6EeFGI" frameborder="0" allowfullscreen></iframe>
