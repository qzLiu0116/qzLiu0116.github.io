---
title: Development of a Virtual Simulation Platform for Real-time Motion Planning of Unmanned Aerial Vehicles in Alleyway Environments
# event: NetSci 2022


# location: Tianjin (Online)


summary: The application of motion planning for UAV in tunnel environment
# abstract: Autonomous flight of UAVs in tunnel environments often faces problems such as narrow environment, complex obstacles, and low visibility, which brings great challenges to the safe flight test of UAVs. In response to this challenge, a virtual simulation platform for real-time motion planning and control of UAVs in tunnel environments is developed. Its overall flow chart is shown in Figure 1. First, a virtual simulation environment based on Gazebo is built, and the ODE physics engine and OpenGL rendering module integrated in Gazebo are used to improve the authenticity of the built tunnel environment; secondly, a real-time motion planning algorithm for UAVs under multiple obstacles is designed, and virtual cameras and lidar sensors are used to obtain environmental information for map construction, and model prediction path integral control is used as the nominal controller to generate the optimal nominal trajectory to solve the problem of safe obstacle avoidance flight of UAVs in virtual tunnel environments; thirdly, a UAV trajectory tracking auxiliary controller based on differential manifolds is designed. The controller includes a trajectory tracking controller and an attitude controller, which tracks the optimal trajectory at a higher frequency, thereby ensuring the robustness of the UAV in the face of uncertain external interference during flight; finally, in order to verify the simulation degree of the designed virtual environment and the real-time, effectiveness and robustness of the proposed UAV motion planning and control algorithm, a UAV flight demonstration verification for the virtual tunnel environment is carried out.

# abstract: Finding an optimal set of key nodes in a network whose removal from the network would dismantle the network is one of the fundamental research problems of Network Science. In this paper, we introduce an entanglement-based dismantling framework, which captures the network's transport properties and enables new insights into the intrinsic topological features of the complex system.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# date: "2022-07-01"
# date_end: "2022-07-06"
# all_day: true

draft: false

authors: 
- admin
  
tags: []
# tags:
# - Source Themes
featured: false

# Is this a featured talk? (true/false)
# featured: true


links:
- icon_pack: 
  icon: 
  name: "Bilibili"
  url: https://www.bilibili.com/video/BV1vc41147Df/?spm_id_from=333.1007.top_right_bar_window_default_collection.content.click&vd_source=e060cbe71c18d308e963782a155bf798
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "media/video/tunnel-demo.mp4"



# Enable math on this page?
math: true
---

## Project Overview:

Autonomous flight of UAVs in tunnel environments often faces problems such as narrow environment, complex obstacles, and low visibility, which brings great challenges to the safe flight test of UAVs. In response to this challenge, a virtual simulation platform for real-time motion planning and control of UAVs in tunnel environments is developed.

Firstly, a virtual simulation environment based on Gazebo is built, and the ODE physics engine and OpenGL rendering module integrated in Gazebo are used to improve the authenticity of the built tunnel environment; 

Secondly, a real-time motion planning algorithm for UAVs under multiple obstacles is designed, and virtual cameras and lidar sensors are used to obtain environmental information for map construction, and model prediction path integral control is used as the nominal controller to generate the optimal nominal trajectory to solve the problem of safe obstacle avoidance flight of UAVs in virtual tunnel environments; 

Thirdly, a UAV trajectory tracking auxiliary controller based on differential manifolds is designed. The controller includes a trajectory tracking controller and an attitude controller, which tracks the optimal trajectory at a higher frequency, thereby ensuring the robustness of the UAV in the face of uncertain external interference during flight;

Finally, in order to verify the simulation degree of the designed virtual environment and the real-time, effectiveness and robustness of the proposed UAV motion planning and control algorithm, a UAV flight demonstration verification for the virtual tunnel environment is carried out.
