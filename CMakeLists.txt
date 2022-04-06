cmake_minimum_required(VERSION 3.20)
project(E1_git_example_image_viewer_exercise)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(E1_git_example_image_viewer_exercise
        BitmapImage.cpp
        BitmapImage.h
        main.cpp)
