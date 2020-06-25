cmake_minimum_required(VERSION 2.8.3)
project(usb_controller)

find_package(catkin REQUIRED COMPONENTS
  joy
  teleop_twist_joy
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)


