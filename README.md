# RoboCup2016RVRL_FieldModels  
6 field models used in RoboCup 2016 Rescue Virtual Robot League.  

## Installing  
    * PLease copy model folders "RC2016VRL_*" and "victim" folder into ~/.gazebo/models  

## Usage  
    Please execute gazebo with a world file which you want to use.  
    EX.)  

    $ gazebo RC2016VRL_PreLiminary1.world  

## Locations of victims and spawning robots  
    See _VictimAndRobotsPlacement.txt  

## Attention  
    The final run2 field model has an issue which there is a invisible object.  
    The invisible object is detected by a laser range finder and any robots can go run over it.  

