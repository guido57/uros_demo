# Overview
* This is a PlatformIO demo program to create a ROS2 publisher and subscriber by an ESP32
* I used an "ESP32 D1 Mini" but any ESP32 should be ok
* This program uses the micro-ROS release created for PlatformIO you can find here: https://github.com/micro-ROS/micro_ros_platformio

# Build and run

## Download this project
* git clone or download this project
* open it with VS Code
* create the file credentials.h in the src directory
* fill it with your wifi and ros2 agent credentials

  e.g.
  ```
  String ssid = "ssid_name"
  String pass = "ssid_password"
  IPAddress ros2_agent_ipa = IPAddress(192,168,1,13);
  int ros2_agent_port = 8888;
  ```

## Run the micro-ROS agent on a PC in your network


## Run this firmware
* build and upload this firmware to your ESP32
 
## Test

My PC has Ubuntu 22.04 with ROS2 Humble


