cmake_minimum_required(VERSION 3.0)
project(squares)
find_package(OpenCV REQUIRED)
add_executable(squares test.cpp)
target_link_libraries(squares ${OpenCV_LIBS})
