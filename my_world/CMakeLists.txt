cmake_minimum_required(VERSION 3.8)
project(my_world)

# find dependencies
find_package(ament_cmake REQUIRED)


install(DIRECTORY
  config launch maps rviz
  DESTINATION share/${PROJECT_NAME}/
)

ament_package()
