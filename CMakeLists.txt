# Version CMake
cmake_minimum_required(VERSION 3.1)

# Project name
project(main CXX)

# Option
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0")

# Source files
set(SOURCES src/main.cpp)

# Compiling target
add_executable(${PROJECT_NAME} ${SOURCES})

# Link target
target_link_libraries(${PROJECT_NAME})
