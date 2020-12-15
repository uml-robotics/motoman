cmake_minimum_required(VERSION 3.0.2)

project(motoman_gazebo)

find_package(catkin REQUIRED)

catkin_package()

#TODO: Add tests

install(DIRECTORY launch controller DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
