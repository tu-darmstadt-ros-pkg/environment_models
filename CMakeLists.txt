cmake_minimum_required(VERSION 2.8.3)
project(environment_models)

find_package(catkin REQUIRED)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES environment_models
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

install(DIRECTORY launch Media urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
