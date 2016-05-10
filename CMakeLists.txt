cmake_minimum_required(VERSION 2.8.3)
project(cat_herb)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  message_generation
  rospy
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES cat_herb
#  CATKIN_DEPENDS message_generation rospy
#  DEPENDS system_lib
)


include_directories(
  ${catkin_INCLUDE_DIRS}
)


