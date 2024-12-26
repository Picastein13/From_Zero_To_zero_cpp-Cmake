# Specify the minimum CMake version required
cmake_minimum_required(VERSION 3.10)

# Set the project name
project(Cpp_Prj)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(Cpp_Prj src/main.cpp)

