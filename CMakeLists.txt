cmake_minimum_required(VERSION 3.15)
project(CppLearning)
set(CMAKE_CXX_STANDARD 20)
add_executable(app 
src/main.cpp
src/calculator.cpp)
target_include_directories(app PRIVATE include)
