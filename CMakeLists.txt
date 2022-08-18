cmake_minimum_required(VERSION 3.23)
project(RenderHelp)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(RenderHelp
        Model.h
        RenderHelp.h
        sample_01_triangle.cpp
        sample_02_texture.cpp
        sample_03_box.cpp
        sample_04_gouraud.cpp
        sample_05_model.cpp
        sample_06_normal.cpp
        sample_07_specular.cpp)
