cmake_minimum_required(VERSION 3.0)
project(screenrotator)

find_package(Qt5 REQUIRED COMPONENTS Gui Widgets X11Extras Sensors DBus)

set(CMAKE_AUTOMOC ON)
set(CMAKE_AUTORCC ON)
add_subdirectory(src)
