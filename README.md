# DT-CRANES: Scene Coordinate Regression–Based Spatial Awareness for Advanced Multi-Crane Safety Monitoring in Construction Sites
DT-CRANES is a vision-based framework for real-time multi-crane safety monitoring using Scene Coordinate Regression (SCR). It directly estimates 6-DoF crane tip poses from monocular images without feature matching or additional sensors.Crane-mounted and drone imagery are fused to build scene-specific spatial representations and integrated into NVIDIA Omniverse digital twin for real-time visualization and automated near-collision detection.
## Proposed Approach
![image](figures/Framework.png)
## Sample results
#### Data Collection
Drone and Crane-mounted camera for data collection
![image](figures/Data_collection.png)
#### Visual Localization
Performance of crane-tip localization
| Crane 1 | Crane 2 |
|--------|---------|
| ![image](figures/pose_crane_1.png) | ![image](figures/pose_crane_2.png) |
#### NVIDIA Omniverse Digital Twin 
Performance of crane-tip localization
| Safety | Near-Collision|
|--------|---------|
| ![image](figures/qualitative_safe.png) | ![image](figures/qualitative_near_collision.png) |
## Demo
