cmake_minimum_required(VERSION 3.1)

file(GLOB ShapeGlob *.cpp)

add_library(SHAPE OBJECT ${ShapeGlob})