cmake_minimum_required(VERSION 3.28.3)

project(ByteCraft_Allocator VERSION 1.0 DESCRIPTION "High-performance memory allocator for C++")

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(ByteCraft_Allocator src/main.cpp)

target_include_directories(ByteCraft_Allocator PUBLIC ${PROJECT_SOURCE_DIR}/include)

