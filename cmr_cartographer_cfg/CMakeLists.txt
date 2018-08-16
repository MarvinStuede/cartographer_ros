cmake_minimum_required(VERSION 2.8.3)
project(cmr_cartographer_cfg)
find_package(catkin)
catkin_package()
install(DIRECTORY launch cfg
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
