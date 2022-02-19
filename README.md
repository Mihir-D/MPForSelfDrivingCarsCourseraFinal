## (Coursera) Motion Planning for Self Driving cars: Final Project

#### Note
Not providing the coursera map here.

### Launch Carla Simulator
```
./CarlaUE4.sh /Game/Maps/Course4 -windowed -carla-server -benchmark -fps=30 -resX=640 -resY=480
```

### Launch Autonomous Driver
```
git clone git@github.com:Mihir-D/MPForSelfDrivingCarsCourseraFinal.git ~/opt/CarlaSimulator/PythonClient/
cd ~/opt/CarlaSimulator/PythonClient/MPForSelfDrivingCarsCourseraFinal
python3 module_7.py 
```