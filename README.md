## Package
install this requirement directly only for downloading python libs
```bash
pip install -r requirements.txt
```  
Access into this requirement file to download required ros packages

## Simulation in Gazebo
```bash
roslaunch final gazebo.launch
```  

## Simulation in rviz
```bash
roslaunch final display.launch
```

## Autonomous map scanning
```bash
roslaunch final display.launch
```

## Nagivation manually through 2d navigation arrow
```bash
roslaunch final move_base.launch
```

## For human following
```bash
rosrun final mobilenet_human_following.py
```
