---
title: Intern in Autel Robotics
# event: NetSci 2022


# location: Tianjin (Online)


summary: The Development of a multi-UAVs inteligent System.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-09-15"
date_end: "2024-03-31"
all_day: true

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
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "media/video/dt.mp4"



# Enable math on this page?
math: true
---

# Intern Overview:

During my intern within the motion planning and decision department, I have made some contributions to the development of a multi-UAVs inteligent system. 

## The overview of the developed system:
 In a complex environment teeming with real and decoy targets, a swarm of quadrotor UAVs is tasked to search for and identify authentic targets, reporting their findings to the ground station. Upon receiving the attack command, "attacker" UAVs are dispatched to neutralize the targets. This mission is facilitated by an integrated multi-UAV intelligent system, encompassing decision-making, planning, and control modules and so on. To streamline development, each module operates independently, activated through the logical sequence of the behavior tree framework. This approach simplifies the process, ensuring efficient execution of the mission.


## Contributions:
**1.Development of a Behavior Tree-based Module-Scheduling Method:** I spearheaded the creation of a novel module-scheduling approach that leverages the robustness of behavior trees. This method provides a systematic way to schedule and manage the execution of various modules within the multi-UAV system, ensuring a harmonious and efficient operation.

**2.Encapsulation of Motion Planning and Decision Algorithms:** I encapsulated the complex algorithms for motion planning and decision-making into a set of rules that govern the construction of modules within the behavior tree. This encapsulation not only simplifies the process of designing individual modules but also enhances the overall modularity and scalability of the system.

**3.Development of Formation Assembly and Keeping Modules:** I developed advanced modules for formation assembly and maintenance, employing the leader-follower concept. These modules enable a fleet of 15 UAVs to fly in coordinated formations, adapting to different shapes and patterns as required by the mission. 

**4.Flexible Code Reusability with Behavior Tree Framework:** I designed the system with a focus on code reusability, allowing for the flexible construction of new task modules. By utilizing the framework of behavior trees, we can logically connect previously built sub-task modules to form new tasks, all defined by a self-created behavior tree logic. This approach significantly reduces development time and increases the adaptability of the system to various mission requirements.
