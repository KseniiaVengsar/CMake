cmake_minimum_required(VERSION 3.22.0)
project(classes)

# Добавляем пути к исходным файлам
add_executable(classes_exe
    Hierarchy_of_classes/Hierarchy_of_classes.cpp
    Hierarchy_of_classes/Equilateral_triangle.cpp
    Hierarchy_of_classes/Figure.cpp
    Hierarchy_of_classes/Isosceles_triangle.cpp
    Hierarchy_of_classes/Parallelogram.cpp
    Hierarchy_of_classes/Quadrangle.cpp
    Hierarchy_of_classes/Rectangle.cpp
    Hierarchy_of_classes/Rhombus.cpp
    Hierarchy_of_classes/Right_triangle.cpp
    Hierarchy_of_classes/Square.cpp
    Hierarchy_of_classes/Triangle.cpp
)
# Добавляем пути к заголовочным файлам
include_directories(
    Hierarchy_of_classes/Equilateral_triangle.h
    Hierarchy_of_classes/Figure.h
    Hierarchy_of_classes/Isosceles_triangle.h
    Hierarchy_of_classes/Parallelogram.h
    Hierarchy_of_classes/Quadrangle.h
    Hierarchy_of_classes/Rectangle.h
    Hierarchy_of_classes/Rhombus.h
    Hierarchy_of_classes/Right_triangle.h
    Hierarchy_of_classes/Square.h
    Hierarchy_of_classes/Triangle.h
)

