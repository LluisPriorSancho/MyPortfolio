# MyPortfolio

## About Me
I am a recent  master student graduate with a degree in Automatic control from the Universitat Politecnica de Catalunya. I specialize in mobile robotics with a strong focus on Python and C++ and its implementations using ROS1 and ROS2. My passion lies in developing autonomous systems and algorithms that enhance the capabilities of mobile robots.

## Projects

### My Functions project
This repository contains a set of functions in different programming languages to be used in future projects. Project in development.
<details open>
<summary><b>More details:</b></summary> 

**Technologies:** Python. Next: C++

**Link:** [GitHub Repository](https://github.com/LluisPriorSancho/MyFunctions) 
</details>

### Cooperative Multi-Modal Robots for Autonomous Coverage Path Planning
This project enables the use of a couple of multi-modal robots for a coverage mission. 
<details open>
<summary><b>More details:</b></summary> 
  
**Summary:** This thesis is inspired from other works which investigates the collaboration between heterogeneous robots for coverage path planning in dynamic environments. This thesis aims to expand into real-life one of those strategies by using a couple of autonomous vehicles for exploration using coverage path planning. The method proposed in this project considers a system with one Unmanned Ground Vehicle (UGV) and one Unmanned Aerial Vehicle (UAV), whose cooperation is controlled using a set of Robot Operating System nodes.

The system creates an exploration plan using the wavefront coverage path planning algorithm for each one of the robots. The system must consider the limitations of the 
robots: an inaccessible area for the Leo rover and the battery scarcity of the DJI Tello drone.

The system integrates a hot swapping subroutine. Once the battery of the drone goes below a threshold, the drone will fly on top of the rover and will land. After landing and outside the scope of this project, the battery can be replaced. With a fully recharged battery, the exploration continuous autonomously.

The location of the robots is obtained using an indoor localization system. This system consists in some antennas installed in the corners of the room that estimates the position of other antennas installed on top of the robots. To increase the accuracy of the estimation for the UGV, a Kalman filter is used. The location of drone is not filtered thus it produces a noisier exploration.

Even though the current studies are focusing in dynamic environments, due to the limitations of the hardware, this project will consider a completely known environment. The incapacity of the robots of obtaining new information regarding present obstacles is outside the scope of this work.

Simulation and real-life testing were conducted in order to validate the behaviour of the system. The resulting exploration in a 6.3x6.3 meters room took approximately 8.30 minutes, including one manual battery change using the hot swap subroutine. The movements done by the UGV and the use of a Kalman filter produced a clear coverage while the disturbances suffered on the drone plus the non-usage of the Kalman filter produced a noisy exploration result.
  
**Technologies:** ROS1, ROS2, Python, C++, Gazebo, Rviz

**Role:** This project is part of my master's project thesis.

**Link:** [GitHub Repository](https://github.com/LluisPriorSancho/CMMR_for_ACPP) 
          [Link to the report](https://drive.google.com/file/d/1O6j72nzqwbA8HTsFL853CV2fNH2on2dY/view?usp=sharing)
</details>

### Game of life
This project creates the game of life by John Conway in C and ncurses using dinamic memory. The project also includes metrics as memory leak checks. 
<details open>
<summary><b>More details:</b></summary> 

**Technologies:** C, ncurses, Make, 

**Role:** This project is part of my master's degree.

**Link:** [GitHub Repository](https://github.com/LluisPriorSancho/GameOfLife.git) 
          [Link to the report](https://drive.google.com/file/d/1W1FBDqMo0KGRYD2TOpgXCV5AOS6FBH8R/view?usp=sharing)
</details>

## Contact
- **Email:** lluis.prior.sancho@gmail.com
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/lluis-prior-sancho/)
- **GitHub:** [GitHub Profile](https://github.com/LluisPriorSancho)
