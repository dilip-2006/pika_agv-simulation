# 🛞 PIKA AGV Bot – ROS Learning Project

A beginner-friendly experimental project where I learned the fundamentals of **ROS robot modeling and simulation** by creating a 2-wheel differential drive AGV with 4 caster wheels, described in **URDF/Xacro** and run inside **Gazebo and RViz**.

---

## 📌 What This Project Represents

This is my very first practical step into ROS and simulation.  
Instead of using pre-made robots, I decided to build my own from scratch so I could learn:

- how robot links and joints are modeled,
- how Xacro reduces repetition in URDF,
- how frames connect the entire robot,
- and how simulations reflect real robot physics.

---

## 🎯 What the Robot Includes

| Component | Description |
|----------|-------------|
| Chassis | Main base frame of the AGV |
| Drive Wheels | 2 powered differential wheels |
| Caster Wheels | 4 supporting wheels to balance the base |
| URDF/Xacro | Parametric model of every part of the robot |
| Gazebo | Physics-based simulation with realistic dynamics |
| RViz | For visualizing the model and TF frames |

---

## 🚀 What I Learned

🔹 URDF fundamentals — inertia, collision, visual  
🔹 How to organize complex robot models using **Xacro macros**  
🔹 How to launch a robot model in **RViz** using `/robot_description`  
🔹 How to spawn the robot into **Gazebo world**  
🔹 The importance of TF and reference frames in robot modeling

This project gave me a strong foundation to expand toward **controls, sensors, SLAM, and navigation**.

---

## ▶️ Launch Commands (Example)

> Adjust based on your ROS version and workspace setup

### Visualize in RViz
```bash
roslaunch agvbot display.launch
