# VSCode_ROS2WorkspaceTemplate
This project contains a template for developing for ROS2 using VSCode on Ubuntu 22.04.  

The files `launch.json` and `tasks.json` contain the custom configurations to BUILD using colcon, and DEBUG by starting a gdbserver and linking to it when the node launches.  

# To get started:
clone this repo into your working Package folder - e.g. ros2_ws/src/<package_name>/

``cd <workspace_root>/src/<package_name>``
``git clone https://github.com/FSTeamNapier/VSCode_ROS2WorkspaceTemplate``

Open your package folder with VSCode (note - you should be editing your code at a package-level in order to unlockthe full power of the launch configuration customisability.  You can also open your project at a workspace-level, but please note that you can only specify one package at a time within the configuration files)

Edit the `settings.json` file as required.  Please note that currently, only C++ packages are supported.  
