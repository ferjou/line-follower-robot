


# 🤖 Line Follower Robot

This project demonstrates the design, modeling, and simulation of an autonomous **line-following robot** using Webots and Python. It was developed as part of a Master's program in Embedded Systems.

---

## 📚 Project Overview

The robot uses two infrared (IR) sensors to detect a black line on a white surface and adjust its movement accordingly using a **proportional control** algorithm.

---

## ⚙️ Technologies Used

- **Python**
- **Webots** (simulation environment)
- **Embedded Systems Concepts**
- **Kinematic & Dynamic Modeling**

---

## 📁 Project Files

- 📄 `rapport_suivant_de_ligne.pdf` – Full academic report (French)
- 🎞 `simulation_vid.mp4` – Webots simulation of the robot
- 📊 `presentation.pptx` – Presentation slides
- 🧠 Python code (included in the report and slides)

---

## 🎥 Demo Video

Watch the full simulation here:  
[![Watch the video](https://img.youtube.com/vi/D0jhvFZJ5Ok/0.jpg)](https://youtu.be/D0jhvFZJ5Ok?si=vfwZFBf5KskI52Nu)

---

## ⚠️ Important Note

> 🔧 **To run this project successfully, it is strongly recommended to use Webots version **2021**.  
> Using other versions may cause compatibility issues or prevent the simulation from working properly.

---

## 📈 Control Logic

The control system uses sensor values to determine the robot's alignment with the path:
- If drifting **left**, reduce left motor speed or reverse it.
- If drifting **right**, reduce right motor speed or reverse it.
- Speeds are adjusted **proportionally** to the error.

---

## 🧑‍💻 Authors

- **Abderrahman Ferjouchia**
- **Yahia Jaber**

### 🎓 Mohammed V University – Rabat  
**Master’s in Computer Science & Embedded Systems**  
Academic Year: **2024/2025**

---

## 🧪 Simulation Tool

This project was simulated using [Webots](https://cyberbotics.com/) with the **e-puck robot** model.

---

