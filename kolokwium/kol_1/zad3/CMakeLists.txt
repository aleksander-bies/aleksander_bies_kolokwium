cmake_minimum_required(VERSION 3.10)
project(zadanie3)
include_directories(include)
add_executable(zadanie3 src/libtest.cpp)
add_library(Student SHARED src/Student.cpp)
install(TARGETS zadanie3 DESTINATION ./bin)
install(TARGETS Student DESTINATION ./lib)
target_link_libraries(zadanie3 Student)
