# Andbot-Prototype-Integration-Plan

# 0. INTRODUCTION
This document describes the Andbot prototype integration plan.
The integration tasks will be separated into several parts:

* ME Design
* Base
* Body
* Arms
* Head
* Wrists & Grippers

# 1. ME design
## 1.1 Components Status & Readiness
n/a

## 1.2 Tasks & Schedules
* EE + ME to define H/W 3D layout: 10/26 (Rex & Richie)
* ME design: ~11/5 (Andrew & ME design company)
* CNC working samples: ~11/30 (Andrew & ME design company)
* Installation: 12/1 ~ 12/4

## 1.3 Expected Deliveries
* Four working samples parts ready

## 1.4 Issues

# 2. Base
![](https://github.com/wennycooper/Andbot-Prototype-Integration-Plan/blob/master/base.png)

## 2.1 Components Status & Readiness
* Base frame: Mechanical design completed, working on ordering process for manufacturing, should be delivered on 10/28 (by Richie)
* 3D printer:   10/15 delivered
* wheels: 10/17 delivered
* DC motors: 10/19 delivered
* IR cliff sensor: ready
* Bumper sensor: ready
* US sensor: ready
* ROS board (XU3): ready
* MEGA2560 board: ready
* Motor Driver L298N: ready
* Battery: use existing Li battery
* Charger board: use existing charger board
* LidarLite V2: ready
* Servo for LidarLite v2: ready

## 2.2 Tasks & Schedules
* H/W Installation: 12/01 ~ 12/03
* Software Integration for SLAM and gmapping: 12/03 ~ 12/17

## 2.3 Expected Deliveries
* A mobile robot base with two-wheels
* Lidar-Lite v2 on a rotating servo
* Limited ROS slam_gmapping for SLAM
* Limited ROS move_base for navigation
* Bumper, IR and US sensors installed

## 2.4 Issues
* Using LidarLite for slam_gmapping MAY perform badly

# 3. Body
## 3.1 Components Status & Readiness
* Neck servo
* LidarLite 
* Servo for LidarLite 
* IR sensor
* Servos for IR sensor

## 3.2 Tasks & Schedules
* ME(Richie) to define 3D H/W layout: 10/26 
* Installation: 12/03 ~ 12/07
* Softwate Integration & testing: 12/07 ~ 12/11

## 3.3 Expected Deliveries
* Rotating neck
* Rotating LidarLite
* Rotating IR sensors for obstacle avoidance

## 3.4 Issues


# 4. Arms (without gripper and wrist)
![](https://github.com/wennycooper/Andbot-Prototype-Integration-Plan/blob/master/arms.png)

## 4.1 Components Status & Readiness
* DC motors(3530B): ready
* L298N: ready
* Connecting parts: 11/6 (need redesign for boundary sensors)
* Gears:  10/23
* Boundary hall sensors: x10 x2 xn, purchasing by Rex
* MEGA2560: ready
* ATtiny84: x10*n, purchasing by Rex

## 4.2 Tasks & Schedules
* H/W Installation: 12/07 ~ 12/9
* Boundary sensor for calibration: 12/09 ~ 12/15
* PID position control for multiple joints: 12/15 ~ 12/18
* ROS moveit!! for trajectory control: 12/18 ~ 12/25

## 4.3 Expected Deliveries
* two 4DOF-arms installed
* Initial joint pose calibration can be worked
* Joints control via ROS API
* Trajectory speed control

## 4.4 Issues

# 5. Head
## 5.1 Components Status & Readiness
* Speakers
* Gas sensors
* Sound sensors: (Rex to purchase)
* 6x6 LEDs: (Rex to purchase)
* MEGA2560

## 5.2 Tasks & Schedules
* Sensors Installation: 12/10 ~ 12/11
* Sensors Tests: 12/14 ~ 12/15

## 5.3 Expected Deliveries
* Sensors can work
* LEDs can work

## 5.4 Issues

# 6. Wrists & Grippers (TBD)

