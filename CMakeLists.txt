cmake_minimum_required(VERSION 3.10)

project(dk-icp)

find_package(fmt CONFIG REQUIRED)

add_executable(dk-icp main.cpp)

target_link_libraries(dk-icp PRIVATE fmt::fmt)
