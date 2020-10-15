# Tools
---

To set up the environment, first follow the instructions from [here.](https://docs.wpilib.org/en/stable/docs/getting-started/getting-started-frc-control-system/wpilib-setup.html>)  This will get many of the tools installed.   Then look through the following list to add missing tools.


## Build / Edit Tools
### VSCode / Gradle / 3rd Party Tools
This is ths standard environment and is needed to create C++ code, build it and deploy it to the robot.   Install using the instructions found [here.](https://docs.wpilib.org/en/stable/docs/getting-started/getting-started-frc-control-system/offline-installation-preparations.html>) Don't forget the 3rd party tools (we used CTRE and Rev Robotics tools most years.)

### CLION
This is a very good C++ Integrated Development Environment (IDE) from JetBrains.  You can choose to use this instead of VS Code.  It has tools embedded in it to help find errors and refactor code.  If you want to use this get a license from Mr. Wits; use the link in the email for installing the JetBrains tools.

### Gamepad Configuration Tool
When building custom gamepads, this tool is used to program the board to assign certain inputs to particular analog/digital input.  This is installed as part of the NI game specific tools.


## Configuration Management Tools
### GitHub
This is a website where our code is stored using a Git Configuration Management Tool.  Additionally, we create project(s) and use the Kanban board to manage activities.   Visit Our main [github page](https://github.com/orgs/Team302/dashboard).

### GitKraken
This is a desktop interface to Git -- specifically GitHub -- where our code and projects reside.   This makes it easier to interact with the remote repository using a GUI instead of the command line.  We use the free version that can be downloaded from [here.](https://www.gitkraken.com/pricing)


## Documentation Tools
### Doxygen
This allows us to generate documentation from our code.  Using markers in the code will control what gets written.   Download the excutable from [here.](https://www.doxygen.nl/download.html)  Run the wizard to generate the documenation files.

### StarUML
This tool is used to create Unified Modeling Language (UML) diagrams such as Class, Sequence, Use Case, State, etc. for our code.  This tool, while old and not currently maintained, allows us to reverse engineer code into object that we can used to create diagrams (the relationships are already understood).   We use version 5.0.2.1570 (there are other versions that are not compatible or really buggy as well as other similar sounding tools).  It can be downloaded from [here.](https://sourceforge.net/projects/staruml/files/latest/download)  We will be considering switching to DrawIO/Diagrams.net this year. 
### DrawIO / Diagrams . net
This is an online drawing tool that has some UML capabilities.  It doesn't really support reverse engineering but is easy to use.  It is available [at.](https://www.diagrams.net/)


## Driver's Station
### Driver's Station
This is part of the FRC Game Tools that gets installed as part of installing the environment.

### SmartDashboard
This is part of the FRC Game Tools that gets installed as part of installing the environment.  It provides access to logs as well as the ability to show key values or code can read values from it (e.g. tuning a PID).   

### Shuffleboard
This is part of the FRC Game Tools that gets installed as part of installing the environment.  It is a replacement for the SmartDashboard.

### WebComponents
This is a new set of custom dashboard utilities that we could use to build a custom dashboard.  Nothing to install yet.


## Robot Configuration Tools
### RoboRio Configuration Tool
This is part of the FRC Game Tools that gets installed as part of installing the environment.

### Radio Configuration Management Tool
This is used to set up the radio (install firmware, set team number, limit bandwidth to simulate competition environment, etc.).   After a robot has been to a competition, the radio will need to be reconfigured for "home use" using this tool.   When we do demonstrations, we need to make sure the robots we are using have unique team numbers.   The radio, roborio and limelight along with the driverstation being used all need the same team number . The download for the tool is located [here.]( https://docs.wpilib.org/en/stable/docs/getting-started/getting-started-frc-control-system/offline-installation-preparations.html)

### CTRE Phoenix Tuner
This gets installed as part of installing the CTRE 3rd party tools.  It allows the firmware and CAN IDs to be set on the CTRE hardware.  There are some really cool things that can be done as well such as running motors in both open loop and closed loop modes, plotting various property values, etc.   Documentation can be found [here.](https://phoenix-documentation.readthedocs.io/en/latest/)

### Limelight Configuration Tool
Limelight (vision solution) has a series of tools found [at.](https://limelightvision.io/pages/downloads)

### Filezilla
File Transfer (FTP) tool to put files on and retrieve files from the RoboRio.  Can also edit the files as well.   The download can be found [here.](https://filezilla-project.org/)

### Putty
An SSH/Telnet client for accessing files on the RoboRio.  The download can be found [here.](https://www.putty.org/)

## Robot Log Tools
### Rio Log Viewer
This is part of the installation that installs the driverstation.

### Rio Log Viewer 2
This can be downloaded from [here.](https://github.com/orangelight/DSLOG-Reader/releases)


