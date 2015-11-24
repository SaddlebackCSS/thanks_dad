cmake_minimum_required(VERSION 3.3)
project(thanks_dad)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.cpp)
add_executable(thanks_dad ${SOURCE_FILES})
target_link_libraries(thanks_dad sfml-graphics sfml-window sfml-system)