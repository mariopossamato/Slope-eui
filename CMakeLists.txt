cmake_minimum_required(VERSION 4.0)
project(eui
        CXX)
add_library(eui
            "${PROJECT_SOURCE_DIR}/include/eui/SharcArchive.hpp"
            "${PROJECT_SOURCE_DIR}/src/eui/SharcArchive.cpp")
target_include_directories(eui PUBLIC
                           "${PROJECT_SOURCE_DIR}/include")
