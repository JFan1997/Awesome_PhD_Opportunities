## PhD Position at Curtin University

### Project Overview

Autonomous robots have long been recognized for their potential to benefit various industries, achieving significant success worldwide, particularly in controlled environments. Examples include autonomous warehouse robots and urban logistic robots. However, reliable high-level autonomy solutions (level 4 and 5) for field robots, which have a broader application spectrum and larger market, are still lacking. Robust understanding of their diverse and complex 3D environments and safe navigation under dynamic and stochastic conditions remain critically challenging.

To address these challenges, the forefront of current robotics research largely revolves around integrating machine learning techniques. One promising solution is end-to-end deep reinforcement learning (DRL), which learns a policy directly mapping robotic sensory information to robotic actions. However, achieving satisfactory performance with DRL methods typically requires a large dataset, which is expensive to obtain due to the high cost of operating robots, or even infeasible for field robots as they may wear out before the training converges. Additionally, a DRL agent typically lacks safety guarantees due to its required exploration mechanism and has poor generalization capabilities in diverse and unseen environments. These current limitations hinder their real-world applications. The robotics community has proposed various techniques to overcome some of these limitations, including sim2real, offline deep reinforcement learning, safe reinforcement learning, decision transformers, and others. However, no solutions have been developed to overcome all the aforementioned limitations.

On the other hand, the most recent era in artificial intelligence has witnessed the emergence of large multimodal models (LMMs), which possess the profound ability to offer a holistic understanding of the environment and its future states by processing multimodal sensory data. For instance, ImageBind, developed by Meta, can integrate data from six modalities – images, video, depth, thermal imaging, and inertial measurement units (IMUs) – to achieve (super)human-level performance in understanding sensory data. This advancement renders the traditional method of training multiple-task perception stacks, which aims to understand an autonomous robot’s world, unnecessary because LMMs are more versatile, general, and can provide a more reliable, effective, and deeper understanding of their environments. Additionally, the latest progress in AI computing makes it possible to integrate LMMs into the computing unit onboard the robot. However, LMMs are not error-free, so the next layers of mapping the output of LMMs to robot actions should be able to ensure that the robot can perform the allocated tasks normally, even in the presence of perception errors, and that these errors are not catastrophic to both the robot and its environment.

### Aims

This project aims to integrate LMMs’ understanding of field mobile robots’ exteroceptive sensory data, and the outputs of robots’ interoceptive sensors to form a world model of the robot. Based on this new world model, we develop a DRL agent being able to map the state of the world model to robot actions directly to perform allocated tasks safely. The trained DRL agent aims to achieve zero-shot transfer to unseen data.

### Objectives

- To develop an effective way to combine the outputs of both LMMs and robots’ interoceptive sensors to form the state representation for modeling the robot’s world environments.
- To design and train a sample efficient offline DRL agent that maps the world model state to actions for a specific autonomous mobile robot platform.
- To develop a safe exploration mechanism to transform an offline DRL agent to an online DRL agent for its fine-tuning and deployment on a real autonomous robot platform.
- To analyze the agent’s performance of various parameters in the world modeling, DRL agent, and exploration mechanism, and identify the optimal parameter setting.
- To test the effectiveness of the optimized autonomous system paradigm on a real mobile robot in multiple field environments.

### Eligibility Criteria

We are seeking a self-motivated PhD candidate who:

- Is eligible to enroll in PhD programs at Curtin University.
- Holds at least a bachelor’s degree in a relevant field such as Robotics, Computer Science, Engineering (Electrical, Mechanical, Mechatronics), Statistics, or Optimization.
- Demonstrates proficiency in conducting research in both robotics and machine learning.
- Possesses skills in Python programming and application of Machine Learning tools, along with experience with ROS 2 ecosystem.
- Exhibits excellent communication skills and works effectively in a team environment.

### Application Process

Please send your CV, academic transcripts, and a brief rationale for why you want to join this research project via the HDR Expression of Interest form to the project lead researcher, listed below.

Dr. Hui Xie  
B.Eng (HEU), M.Eng (HIT), Ph.D (University of Alberta, Canada)  
Lecturer in Robotics and Automation  
Tel | +61 8 9266 3357  
Email | [hui.xie@curtin.edu.au](mailto:hui.xie@curtin.edu.au)  
Web | [www.curtin.edu.au](https://www.curtin.edu.au)  
School of Electrical Engineering, Computing, and Mathematical Sciences

Thank you for your attention!

Best Regards,  
Viraj Muthugala
