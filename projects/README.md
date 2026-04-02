4-Wheeled Robot Simulation (Webots)
📌 Overview

This project is a 4-wheeled mobile robot simulation developed using Webots. It demonstrates basic robot locomotion and obstacle avoidance using distance sensors and motor control.

The robot can move forward, detect obstacles, and automatically turn to avoid collisions.

🎯 Features
4-wheel drive robot
Obstacle detection using distance sensors
Autonomous obstacle avoidance behaviour
Continuous motion with real-time control
Simple and beginner-friendly implementation
🛠️ Technologies Used
Python
Webots Robot Simulator
📂 Project Structure
├── 4_wheeled_robot.wbt     # Webots world file
├── obstacle_avoidance.py   # Robot controller code
⚙️ How It Works

The robot uses two distance sensors:

Left sensor (ds_left)
Right sensor (ds_right)
Behaviour:
Moves forward by default
If an obstacle is detected:
Robot rotates in place
Avoids collision
Resumes forward motion

From your controller:

If sensor value < 950 → obstacle detected
Robot turns by reversing one side of wheels
▶️ How to Run
Open Webots

Load the world file:

4_wheeled_robot.wbt

Attach the controller:

obstacle_avoidance.py
Click Run ▶️
📸 Simulation Logic (Code Summary)
Initializes robot and sensors
Enables distance sensors
Controls 4 wheels using velocity
Implements obstacle avoidance using a counter-based turning mechanism
🚀 Future Improvements
Add more sensors (front, rear, ultrasonic)
Implement smoother path planning
Integrate computer vision (camera)
Apply SLAM or mapping algorithms
📚 Learning Outcomes
Understanding mobile robot control
Sensor-based decision making
Simulation-based robotics development
Basic autonomous navigation
👨‍💻 Author

Your Name