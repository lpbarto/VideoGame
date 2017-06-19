cmake_minimum_required(VERSION 3.7)
project(VideoGame)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(VideoGame ${SOURCE_FILES})

target_link_libraries( VideoGame sfml-sfml )
target_link_libraries( VideoGame sfml-window )
target_link_libraries( VideoGame sfml--graphics )
target_link_libraries( VideoGame sfml-audio )
target_link_libraries( VideoGame sfml-network )