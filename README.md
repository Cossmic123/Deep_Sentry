Environmentally Oriented Automatic Path-Planning Autonomous Robot

Overview
This project focuses on developing an autonomous robot capable of environment-aware path planning for both open and closed spaces. The system integrates **ROS 2 Humble** and **Gazebo** for simulation, while the hardware implementation is achieved using a **Raspberry Pi 4B (8GB)**–based robot equipped with a **camera, ultrasonic sensors,** and a **line follower**.  
The objective is to create a robot that intelligently navigates by analyzing surroundings, avoiding obstacles, and optimizing travel paths through efficient algorithmic computation.

---

Algorithms Implemented
The system evaluates and compares multiple classical and modern path-planning algorithms to determine efficiency, scalability, and robustness:

- A\*
- Hybrid A\*
- Dijkstra
- Greedy
- BFS
- DFS
- **Our Proposed Model (RRT-Alpha)** — a modified version designed to enhance adaptability and smoothness in complex environments.

---

Technologies Used
| Category | Tools / Components |

| **Simulation** | ROS 2 Humble, Gazebo, RViz |
| **Programming** | Python 3, OpenCV, NumPy |
| **Hardware** | Raspberry Pi 4B (8GB), Ultrasonic Sensors, Camera Module, Line Follower Sensor, Motor Driver |
| **Data Analysis** | Matplotlib, Pandas |
| **Documentation** | LaTeX / Word (IEEE Format), Excel, PowerPoint |

---

Objectives
The main goal is to implement and test a **robust autonomous navigation system** that performs efficiently under variable environmental conditions.  
The project aims to:
- Design and test path-planning algorithms for dynamic and static environments.
- Evaluate performance across parameters such as path efficiency, execution time, smoothness, scalability, and obstacle avoidance.
- Integrate software simulation with real-world hardware implementation.
- Demonstrate real-time adaptability and accuracy in navigation using a cost-effective hardware setup.
  
 ---
 
Result
The proposed algorithm establishes a new benchmark in autonomous path planning by combining efficient trajectory generation, robust obstacle avoidance, and computational scalability — making it a strong candidate for industrial, warehouse, and outdoor autonomous navigation applications.
  


