cmake_minimum_required(VERSION 3.10.2)
project(moveit_resources_franka_panda_description)
find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY launch meshes rviz urdf DESTINATION share/${PROJECT_NAME})
