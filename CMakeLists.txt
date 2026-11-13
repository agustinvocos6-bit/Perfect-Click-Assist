cmake_minimum_required(VERSION 3.21)

project(PerfectClickAssist VERSION 1.0.0)

add_library(${PROJECT_NAME} SHARED
    src/main.cpp
)

target_include_directories(${PROJECT_NAME} PRIVATE src)

setup_geode_mod(${PROJECT_NAME})