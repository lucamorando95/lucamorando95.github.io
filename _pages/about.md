---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
My name is Luca Morando and I am an Italian researcher working in the US. 

Currently, I am a postdoctoral associate at New York University and a Visiting Postdoctoral Scholar at U.C. Berkeley, in particular in the [Agile Robotics and Perception Lab](https://arplaboratory.github.io/)(ARPL), headed by Prof. Giuseppe Loianno. 
At ARPL, I work on aerial robotics autonomy, especially for long range application for fixed wing aircrafts and Human Robot Interaction using Mixed Reality techinques. 

I joined ARPL as a Visiting Ph.D. student in November 2021 where I spent two years before getting my International Ph.D. in Robotics and Autonomous System from the [University of Genoa](https://unige.it/en), under the supervision of both Prof. Loianno and Prof. Antonio Sgorbissa. 
Prior to the Ph.D., I obtained my Master Degree from University of Genoa in Robotics Engineering, where I spent a year in an International Exchange Program at the [Universitè de Technologie de Compiegne (UTC)](https://www.utc.fr/),  where I conducted my Master Thesis project at the [Heudyasic Lab](https://www.hds.utc.fr/en/) under the supervision of Prof. Pedro Garcia. 
I got my bachelor degree as well from University of Genoa in Biomedical Engineering, where I participated to 6 months Interniship at the Italian Institude of Technology. 

My research has been validated through DARPA and Army Research Lab field trials, published in leading IEEE venues, and resulted in multiple journal articles and U.S. patents.


## Ph.D. And Postdoc Research 

Autonomous drones, both wing based and quadrotors, are becoming indispensable in critical missions such as search and rescue and disaster response. Differently from other robotics systems, autonomous drones have the capability to fly, cover long distances and also explored constrained outdoor and indoor environments where other robotics agent would easily fail. Despite this, today's system still lacks fully autonomy capability and they ofter requires expert human pilot intervention. Additionally, despite already used as important tool in emergency scenarios and military applications, still lacks proper mechanism for an intelligent interaction with non expert humans, that can enhance them from simple tools, to real human collaborator and companion in various missions. 
During my research, I fully focused on building autonomous stack based on a simple premise:

*Enabling safe and agile autonomy in unknown environments by adapting to shifting condition, enabling long range and energy harvesting capabilities and provide an enhanced level of collaboaration with humans in complex mission sceanrios.*

### Autonomous and Agile Planning and Control for Fixed Wing Aerial Vehicle
(put video plane flyig during the glide at coney island and image google earth of the paper)
Despite their great potential across domains such as environmental monitoring, disaster response, agriculture, and logistic, unmanned Fixed Wing UAVs, which stand out for their long range endurance, and high cruise speed compared to multirotor aerial vehicles, present a very complex coupled and highly non-linear dynamics, which is strictly affected by aerodynamics effects acting on the airframes at different flying regimes. These characteristics, enhanced by the external wind disturbances, can pose severe problems on planning and control of flight trajectories. In this direction, my research has been focused in designing flying architecture that leverages the complex dynamics of the aircraft, and simplifying them for control objectives leveraging the mathematical formulation provided by the Differential Flatness for geometric control. 
To further keep the plane always in a safe flying envelope, continuous flying trajectories are optimized based on Bernestin Polynomials, with the characteristic of being dynamic aware, wind aware for optimal crusing and able to generate optimal gliding conditions for Energy Harvesting. 
Additionally, we developed a fully dynamic and aerodynamic aware NMPC for optimal tracking of the genrated trajectories and disturbances rejection. 
This framework, tested on various platforms, provides resilient flight autonomy for long range fixed wing applications. 

### Human Robot-Drone Interaction for shared collaboration and exploration of indoor constrained environments through Mixed Reality
During my research I have always been aware that Aerial Robots have the potential to play a crucial role in assisting humans in complex and dangerous
tasks without requiring an expert human pilot that always control them through teleoperation devices based on simple joystics. The goal of my research has been motivated by creating autonomy and interaction solutions to decrease users’ cognitive and physical workload while working with a aerial robotic agent, makig the interaction so natural that the human does not consider them as machines but as real collaborators, that they can trust, and can guide them in dangerous and complicated exploration. In this direction, I develop a bidirectional spatial awareness stack based on a virtual-physical interaction leveraging Mixed Reality interaction tools with the goal to create a virtual immersive environment integrated in the real word where the users and the robots can sinuosly interact and sharing spatial and perception information and control commands minimizimng the user mental loading. 
To achieve this, the user can control the robot giving him spatial waypoints or directly drag the virtual representation in a virtually created environment, visible in Mixed Reality, dynamically enhanced with the robot mapping capabilities. 
Additionally, the user can be guided by the robot as well, which it runs an onboard autonomous pipeline based on generation of obstacles, user and dynamic aware flying trajectories, which acts as a safety guaranteed for the robot navigation, and provides a force feedback to the user if he tries to pull the robot away from it. 
User case studies shows how the bi-directional planner helped spatial awareness based on MR increase the user interaction efficiency thus reducing the workload. Additionally the MR has been developed as a web based framework, cross platform and accessible from anywhere by anyone. 

### Efficient Navigation and Inspection of Large Photovoltaic Solar Plants using autonomous quadrotors
During the first part of my Ph.D. I increased my control and perception knowledge working to a project with an Italian Company experts in using drones for inspections of PV plants. However, despite they were using built-in waypoints based planning stacks to guide the quadrotors above the PV plants, they manifested the desired to actually decrease the insopection time of the PV plants whilke increasing the quality of the dataset collected. I personally adressed this problem as one of the first in Italy, developing an optimization based visual servoing technique to autonomously detect and tracking PV lines in different layouts and meteorlogical scenarios. A machine learning algorithm was merging the features of the PV array when detected by both the thermal and RGB camera, providing a stable center line, which has been tracked and predicted in the future by sophisticated bayesian based trajectory generation tools. 
The project was a success, we inspected a full PV plant in 20% less time of the classic techniques collectiung higher quality data, since able to fly perfectly on the array, at lower altitude, without traversing the terrain in between multiple rows. 
After this, my lab in Genova, won one of the biggest EU project for this kind of tasks, becoming leader in the discipline. 

Together, all these research topic based on aerial robotics, provides to me the skills, the experience and capabilities of creating complex autonomy stacks for various robotics application, that can varies from extending long range capabilities of unmanned fixed-wings, to create human robot collaboration pipelines for natural interaction and shared perception in exploration tasks and finally to create industrial based solutions. 
All of these topics are addressing with rigorous advancement of the state of the art, which results in robusts and avant-garde stack, with outcomes appearing in multiple international publications and workshops. 


## Latest News 
