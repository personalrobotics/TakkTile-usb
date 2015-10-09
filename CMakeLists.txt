cmake_minimum_required (VERSION 2.8.3)

project(takktile_usb)

find_package(catkin REQUIRED)

catkin_package()
catkin_python_setup()
catkin_install_python(PROGRAMS src/TakkTile/TakkTile.py
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

