cmake_minimum_required(VERSION 3.10)
project(myProject)
include_directories(../${CMAKE_SOURCE_DIR})
file(GLOB SOURCES ../*.cpp)
add_executable(myProgram ${SOURCES})

