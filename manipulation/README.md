
This repos holds all the 3rd party dependencies needed for the turtleGripper project.

##1. Openmanipulator. 

The 'open_manipulator_description' is already included in our package due to conflict on URDF between the robot arm and the Kinect. (both URDF has 'camera link'). (After you clone it, delete the open_manipulator_description which is included in turtleGripper.)

## 1. OpenManipulator ???
```jsx
git clone https://github.com/ROBOTIS-GIT/DynamixelSDK.git
git clone https://github.com/ROBOTIS-GIT/dynamixel-workbench.git
git clone https://github.com/ROBOTIS-GIT/dynamixel-workbench-msgs.git
git clone [https://github.com/ROBOTIS-GIT/open_manipulator.git](https://github.com/ROBOTIS-GIT/open_manipulator.git)
```

## 2. Openmanipulator ??

```jsx
git clone https://github.com/ROBOTIS-GIT/open_manipulator_controls.git
git clone https://github.com/ROBOTIS-GIT/open_manipulator_dependencies.git
```

## 3. Navigation_tutorial
```
git clone https://github.com/ros-planning/navigation_tutorials.git
```
Some packages in this repo is utilized for nav_module of tgrip.