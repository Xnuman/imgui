cmake_minimum_required(VERSION 3.30)

project(imgui)

set(ALL_SOURCES 
    imgui.h
    imgui.cpp
)

add_library(imgui STATIC ${ALL_SOURCES})

install(TARGETS imgui )