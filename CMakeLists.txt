PROJECT(CanFestival)
cmake_minimum_required(VERSION 2.4.0)
ADD_DEFINITIONS("-std=c++0x")

#SET(EXECUTABLE_OUTPUT_PATH ${${PROJECT_NAME}_SOURCE_DIR}/bin)
SET(LIBRARY_OUTPUT_PATH ${${PROJECT_NAME}_SOURCE_DIR}/lib)

ADD_DEFINITIONS(-DNOT_USE_DYNAMIC_LOADING)
ADD_SUBDIRECTORY(src)


