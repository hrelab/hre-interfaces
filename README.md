# HRELab Custom ROS 2 Interfaces

This folder can be pulled for all custom ROS 2 interfaces for the HRELab. These are largley customized to this lab, but anyone can use.

## Adding a New Interface

To add a new interface, add the file in the `msg` folder following the format of the others, or your own if you know the format.

Additionally, you will need to add the message to the `CMakeLists.txt` file, in the `rosidl_generate_interfaces()` function.
