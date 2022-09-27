cmake_minimum_required(VERSION 3.22)

project(facebook LANGUAGES CXX)

add_executable(fac threaded_bfs.cpp)

target_compile_options(fac PRIVATE "-std=c++17" "-ggdb3" "-O0")
