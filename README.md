# Andbot-Prototype-Integration-Plan

# 0. INTRODUCTION
This document describes the Andbot prototype integration plan.
The integration tasks will be separate into several parts:
* Base
* Arms
* Body
* Head

# 1. Base
## 1.1 Components Status & Readiness
* base frame: design completed, working on ordering process for manufacturing, should be delivered on 10/28
* 3D printer:   10/15
* wheels: 10/17 delivered
* DC motors: 10/19 delivered
* IR cliff sensor: ready
* Bumper sensor: ready
* US sensor: ready
* ROS board (XU3): ready
* MEGA250 board: ready
* Motor Driver L298N: ready
* Battery: use existing Li battery
* Charger board: use existing charger board
* LidarLite V2: ready
* Servo for LidarLite: ready

## 1.2 Integration Schedule
* 3D printing components: 10/16 ~
* H/W Installation: 10/28 ~ 10/30
* Software Integration for SLAM and gmapping: 10/30 ~ 11/13

## 1.3 Expected Delivery
* A mobile robot base with two-wheels
* Lidar-Lite v2 on a rotating servo
* Limited ROS slam_gmapping for SLAM
* Limited ROS move_base for navigation
* Bumper, IR and US sensors installed

## 1.4 Issues
* Quantity of prototype?  (ME team only order one piece)
* Using LidarLite for slam_gmapping MAY perform badly

# 2. Arms (without gripper and wrist)
## 2.1 Components Status & Readiness
* DC motors(3540): ready
* L298N: ready
* Connecting parts: 11/6 (need redesign for boundary sensors)
* Gears:  10/23
* Boundary hall sensors: x10*2*n, purchasing by Rex
* MEGA2560: ready
* ATtiny84: x10*n, purchasing by Rex

## 2.2 Integration Schedule
* H/W Installation: 11/6 ~ 11/9
* Boundary sensor for calibration: 11/9 ~ 11/13
* PID position control for multiple joints: 11/16 ~ 11/20
* ROS moveit!! for trajectory control: 11/23 ~ 11/27

## 2.3 Expected Delivery
* two 4DOF-arms installed
* Initial joint pose calibration can be worked
* Joints control via ROS API
* Trajectory speed control

## 2.4 Issues
* need to define final product spec for 2DOF or 4DOF arms
* Need to consider how to install the arms on base?

# 3. Body (TBD)

# 4. Head (TBD)


