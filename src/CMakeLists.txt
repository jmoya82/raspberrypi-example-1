# Minimum CMake version required to generate 2 
# our build system
cmake_minimum_required(VERSION 3.0)

# Name of our Project
project(raspberrypi-example-1)

# add_executable creates an executable with 
# The given name. In our case it is "Hello"
# Source files are given as parameters. In our 
# Case we only have one source file hello_world.cpp 
add_executable(hello hello_world.cpp)