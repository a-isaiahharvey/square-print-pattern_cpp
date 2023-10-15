# Set the minimum required version of CMake
cmake_minimum_required(VERSION 3.10)

# Set the project name and version
project(SquarePrintPattern VERSION 1.0)

# Set the C++ standard to 11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add an executable target with the source file
add_executable(SquarePrintPattern square_print_pattern.cpp)
