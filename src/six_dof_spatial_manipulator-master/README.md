## QUESTION 3 for Interplanetar Software Recruitment 2024 


#### Some Notes

1.   You should have ROS Noetic installed on Ubuntu 20.04. Follow [this](https://wiki.ros.org/noetic/Installation/Ubuntu) link if you don't have ROS installed. Choose ROS Noetic Desktop Full Option

2.   Install the following dependencies also:

    sudo apt-get update
    
    sudo apt-get install ros-noetic-move-base-msgs

    sudo apt install ros-noetic-moveit -y

    sudo apt-get install ros-noetic-ros-control ros-noetic-ros-controllers
  
    sudo apt install ros-noetic-joint-state-publisher-gui

    

3.  It is advised to install VS Code and the ROS extension from Microsoft while rendering the URDF

    Install VS Code from the [.deb package](https://go.microsoft.com/fwlink/?LinkID=760868)

    From the left 'Extension' panel, search and install the 'ROS' extension (from Microsoft) 

    Switch to the pre-release version after the ROS extension installation.

    It should look like this:

    ![image](https://github.com/InterplanetarCodebase/six_dof_spatial_manipulator/assets/100117385/052afb70-e53e-4f97-8fb0-bfa48c3f9c73)

    Enable Autosave from the 'File' tab for live rendering

    <b>Side Note</b>: Avoid signing into your GitHub or Microsoft account from VS Code, as it may install unwanted extensions from your previous VS Code environments (_if any_) and cause problems
