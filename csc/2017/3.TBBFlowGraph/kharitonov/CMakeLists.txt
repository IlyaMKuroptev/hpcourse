cmake_minimum_required(VERSION 2.8)
project(flows)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -Wall")
add_executable(${PROJECT_NAME} "flow.cpp")
target_link_libraries(flows -ltbb)
