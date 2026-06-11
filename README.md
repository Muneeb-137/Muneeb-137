# Hi, I'm Muneeb Asif 👋

**Software Engineering new grad from Western University**  
Full-stack • Machine Learning • Computer Vision • Robotics • Cloud

I build practical software systems that connect AI, real-world data, and user-focused applications. My work includes computer vision for medical imaging, intelligent surveillance, machine learning pipelines for telemetry analysis, reinforcement learning for robotic manipulation, and full-stack/mobile applications.

---

## Project Summary

**One sentence:**  
I build real-world AI and software engineering projects that combine computer vision, machine learning, robotics, and full-stack development to solve practical problems in healthcare, automation, and intelligent systems.

---

## Featured Projects

### 🏥 Ctrl-and-Incision — Image-Guided 3D Ultrasound Reconstruction System

A capstone project focused on building a 3D ultrasound reconstruction workflow for image-guided surgery. The system converts tracked 2D ultrasound frames into 3D volumetric data and supports calibration, acquisition, reconstruction, and visualization.

**What it does**
- Captures 2D ultrasound frames with spatial tracking data.
- Converts tracked image slices into 3D reconstructed volumes.
- Supports calibration workflows for camera, stylus, and hand-eye alignment.
- Visualizes reconstructed medical volumes using VTK and 3D Slicer.

**Key achievements**
- Built an end-to-end reconstruction pipeline using Python, Plus Toolkit, and VTK.
- Integrated NDI Aurora tracking with ultrasound acquisition through PlusServer.
- Implemented calibration workflows using OpenCV and ArUco markers.
- Improved reconstruction reliability through intrinsic, pivot, and hand-eye calibration.
- Validated reconstructed `.mha` volumes in 3D Slicer.
- Placed **Top 6 out of 36+ teams** at the Western Engineering Design Showcase.

**Tech stack**  
Python, OpenCV, ArUco, Plus Toolkit, VTK, 3D Slicer, PySide6, NDI Aurora

**Project in one sentence:**  
An image-guided surgery system that turns tracked 2D ultrasound scans into accurate 3D volumes for medical visualization and surgical navigation.

---

### 💎 Jewelry Surveillance AI — Real-Time Retail Security Vision System

A computer vision security prototype designed for jewelry stores. The system detects people, face coverings, movement near display cases, and suspicious behavior patterns using zone-based monitoring and risk scoring.

**What it does**
- Detects people in real time using YOLO.
- Classifies face covering status such as masked, unmasked, or covered.
- Monitors high-value display-case zones.
- Detects suspicious motion near cases or entrances.
- Produces risk scores instead of flagging normal movement as suspicious.

**Key achievements**
- Built a real-time OpenCV and YOLO-based surveillance pipeline.
- Trained a face-covering classifier using TensorFlow/Keras.
- Created zone-based motion logic for display cases and entrance areas.
- Designed suspicious-motion scoring that considers speed, direction, and region of interest.
- Reduced false alerts by separating normal movement from abnormal behavior.
- Built the project around practical real-world retail security use cases.

**Tech stack**  
Python, OpenCV, YOLOv8, TensorFlow/Keras, NumPy, Computer Vision

**Project in one sentence:**  
A real-time computer vision security system that detects people, face coverings, and suspicious movement near jewelry display cases.

---

### 🔋 Battery Analyzer — Inverter Telemetry Machine Learning Pipeline

A machine learning pipeline for predicting inverter overheating risk using telemetry data. The project processes temperature, current, voltage, and speed logs to build classification and regression models.

**What it does**
- Cleans raw telemetry CSV files.
- Converts logs into structured time-series datasets.
- Builds models for overheating and delta-temperature prediction.
- Supports analysis and validation of machine learning model outputs.

**Key achievements**
- Built an end-to-end telemetry processing pipeline using Python, Pandas, and NumPy.
- Standardized raw CSV logs into clean 1Hz time-series datasets.
- Developed classification and regression models using Scikit-learn.
- Improved anomaly detection accuracy through model experimentation.
- Reduced manual diagnostics and preprocessing work using reusable scripts.

**Tech stack**  
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook, Machine Learning

**Project in one sentence:**  
A machine learning pipeline that transforms raw vehicle telemetry into overheating risk predictions and diagnostic insights for performance analysis.

---

### 🤖 Reinforcement Learning Robotic Arm — SAC + HER in PyBullet

A reinforcement learning project where a robotic arm learns reaching, grasping, and object placement behavior in simulation. The project uses continuous-control reinforcement learning with SAC and SAC + Hindsight Experience Replay.

**What it does**
- Simulates a robotic arm in PyBullet.
- Defines a continuous-control manipulation environment.
- Trains agents to complete reaching and object-placement tasks.
- Uses reward shaping and HER to improve learning from sparse rewards.

**Key achievements**
- Designed a custom robotic manipulation environment using Python and PyBullet.
- Implemented Soft Actor-Critic training for continuous control.
- Added SAC + Hindsight Experience Replay to improve sparse-reward learning.
- Improved task success rate compared to the base agent.
- Built training analysis workflows to monitor reward, stability, and convergence.
- Structured the project so it can support both simulation and future real-arm deployment.

**Tech stack**  
Python, PyBullet, Gymnasium, Stable-Baselines3, PyTorch, NumPy, Reinforcement Learning

**Project in one sentence:**  
A reinforcement learning robotic arm simulation where an agent learns reaching, grasping, and placement tasks using SAC and Hindsight Experience Replay.

---

### 🎓 Western University Chatbot — Student Support Assistant

A full-stack chatbot designed to help Western University students find information about academic services, OSAP, registration, graduation, and counselling workflows.

**What it does**
- Provides student-support answers through a chatbot interface.
- Routes users through multiple university-service workflows.
- Organizes FAQ information into reusable modules.
- Supports future NLP expansion.

**Key achievements**
- Built a full-stack chatbot using Next.js, React, TypeScript, Tailwind CSS, Node.js, and Python.
- Implemented conversational routing for multiple student-service workflows.
- Created reusable frontend components for chatbot, FAQ, help, and service pages.
- Improved maintainability by organizing academic topics into reusable response modules.

**Tech stack**  
Next.js, React, TypeScript, Tailwind CSS, Node.js, Python, NLP Systems

**Project in one sentence:**  
A full-stack student support chatbot that helps students navigate university services through structured conversational workflows.

---

### 🩺 HealthCare Camp Mobile App — Patient Data Collection System

A mobile application for patient registration and healthcare camp data collection. The app digitizes intake workflows and improves how patient records are collected, stored, and accessed.

**What it does**
- Allows patients to be registered digitally.
- Collects questionnaire and health intake information.
- Stores structured patient records.
- Helps healthcare staff access patient data more efficiently.

**Key achievements**
- Developed a mobile app using React Native, Node.js, and SQL.
- Digitized manual healthcare camp registration workflows.
- Reduced manual data-entry errors through structured forms.
- Improved processing efficiency for healthcare staff.
- Designed a clean user interface for fast field use.

**Tech stack**  
React Native, Node.js, SQL, JavaScript/TypeScript, Mobile Development

**Project in one sentence:**  
A mobile healthcare intake application that digitizes patient registration and makes camp data collection faster, cleaner, and more reliable.

---

## Skills

**Languages**  
Python, JavaScript, TypeScript, Java, C/C++, SQL, HTML, CSS

**Machine Learning & AI**  
PyTorch, TensorFlow, Scikit-learn, NumPy, Pandas, Matplotlib, Reinforcement Learning, Computer Vision

**Frameworks & Libraries**  
React, React Native, Node.js, Express.js, Flask, PySide6, OpenCV, VTK, Gymnasium, Stable-Baselines3

**Tools & Technologies**  
Git, GitHub, Docker, PostgreSQL, MySQL, Google Cloud Platform, PyBullet, Plus Toolkit, 3D Slicer, VS Code, Linux, REST APIs

---

## What I Am Focused On

I am currently focused on building portfolio projects in:

- Computer vision systems for real-world monitoring and automation
- Reinforcement learning and robotics simulation
- Medical imaging and 3D visualization
- Full-stack applications with AI features
- Machine learning pipelines for structured and time-series data

---

## Contact

- **LinkedIn:** linkedin.com/in/muneeb-asif-260113121  
- **GitHub:** github.com/Muneeb-137  
- **Email:** masif25@uwo.ca
