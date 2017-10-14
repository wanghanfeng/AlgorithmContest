cmake_minimum_required(VERSION 3.5)
project(AlgorithmContest)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp 5_8_Unix_Is/UnixIs.cpp)
add_executable(AlgorithmContest ${SOURCE_FILES})