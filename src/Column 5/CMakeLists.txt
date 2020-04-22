cmake_minimum_required(VERSION 3.10)

# set the project name and version
project(BinarySearch VERSION 1.0)

# specify the C++ standard
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED True)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# add the executable
add_executable(BinarySearch search.c)

# enable testing
enable_testing()

# does the application run
add_test(NAME Runs COMMAND BinarySearch)
