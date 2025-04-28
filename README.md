## 🦋 Used models from the Mathworks Team

- Train Kinova RoboArm https://www.mathworks.com/help/reinforcement-learning/ug/train-sac-agent-for-ball-balance-control.html
- Mars Rover https://www.mathworks.com/help/sm/ug/mars_rover.html
## 🪲 GUIDE

- Open project file `rlKinovaBallBalance.prj`
- Run `TrainSACAgentForBallBalanceControlExample.mlx` script
- For 3d visualisation, change `Visualisation` option from `None` to `3D Mesh`

## 🐧 DATA

### Control.Drive
struct with fields:

                Kp: 10000
                Ki: 50
                Kd: 10
                 N: 1000
       FiltTargetw: 0.0500
       FiltSensorw: 0.0100
    TrqCmdLimitPos: 500
    TrqCmdLimitNeg: -500
       TargetSpeed: 0.1000
       TargetAccel: 0.5000
         StartTime: 1
         
## 🐒 Main scheme

![alt text](https://github.com/zhus-dika/train_mars_rover-kinova_roboarm/blob/main/images/main_scheme.png)    

## 🦚 Results

![Alt Text](https://github.com/zhus-dika/train_mars_rover-kinova_roboarm/blob/main/images/mars_rover%2Bkinova_roboarm_compressed.gif)D
