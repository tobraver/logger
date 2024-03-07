cmake_minimum_required(VERSION 3.1.0)

project(logger_example CXX)

add_executable(logger_example example.cpp)

# -l
target_link_libraries(logger_example PRIVATE logger)
