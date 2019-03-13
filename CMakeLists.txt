
cmake_minimum_required(VERSION 3.13)
project(KINU)

set(CMAKE_CXX_STANDARD 14)

add_library(KINU Component.cpp
Component.hpp
Config.hpp
Entity.cpp
Entity.hpp
EventsManager.cpp
EventsManager.hpp
Pool.hpp
SystemsManager.cpp
SystemsManager.hpp
World.cpp
World.hpp)
