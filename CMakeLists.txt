cmake_minimum_required(VERSION 3.10.0)

project (HelloWrld)

add_executable(HelloWrld ${PROJECT_SOURCE_DIR}/main.cpp)
target_link_libraries(HelloWrld)