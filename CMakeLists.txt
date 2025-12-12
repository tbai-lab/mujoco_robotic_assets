cmake_minimum_required(VERSION 3.0.2)
project(mujoco_robotic_assets)

find_package(catkin)

install(DIRECTORY resources
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
