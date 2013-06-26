cmake_minimum_required(VERSION 2.8 FATAL_ERROR)

project(openni_organized_edge_detection)

find_package(PCL 1.2 REQUIRED)

include_directories(${PCL_INCLUDE_DIRS})
link_directories(${PCL_LIBRARY_DIRS})
add_definitions(${PCL_DEFINITIONS})

add_executable (openni_organized_edge_detection openni_organized_edge_detection.cpp)
target_link_libraries (openni_organized_edge_detection ${PCL_LIBRARIES})
