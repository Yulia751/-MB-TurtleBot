# TurtleBot Mobile Robotics Project

## 📌 Project Overview
This project focuses on developing a **lane detection and autonomous navigation system** for a TurtleBot using camera-based vision processing. The primary objective is to utilize **image filtering and computer vision techniques** to detect lane markings, navigate within predefined paths, and ensure obstacle avoidance.

## 🚀 Features
- **Lane Detection**: Uses computer vision to detect lanes on the road.
- **Edge and Color Filtering**: Filters out unnecessary details to extract relevant lane markings.
- **Autonomous Navigation**: Uses processed vision data to control TurtleBot movement.
- **Obstacle Detection**: Identifies and avoids obstacles in the robot's path.

## 🛠 Technologies Used
- **Hardware**:
  - TurtleBot 3 (Burger)
  - Camera Sensor 
  - Microcontroller
- **Software & Frameworks**:
  - Robot Operating System (ROS Noetic)
  - Python

## 🔧 Installation & Setup
### 1️⃣ Prerequisites
- Ubuntu 20.04 LTS (or ROS-compatible OS)
- ROS Noetic installed (`ros-noetic-desktop-full`)
- Dependencies:
  ```bash
  sudo apt update && sudo apt upgrade -y
  sudo apt install ros-noetic-cv-bridge ros-noetic-image-transport -y
  ```
- Clone the project repository:
  ```bash
  git clone https://github.com/yourusername/turtlebot_project.git
  cd turtlebot_project
  ```

### 2️⃣ Running the TurtleBot
```bash
roslaunch turtlebot_bringup minimal.launch
```

## 📖 Usage
- **Start Camera Streaming**:
- **Run Lane Detection Algorithm**:
- **Move the Robot Based on Processed Image Data**:


## 🏆 Contributors
- **[Yulia Isaeva]** 
- **[Jonathan Lowrie]**
