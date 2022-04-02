cmake_minimum_required(VERSION 3.19)
project(Vector C)

set(CMAKE_C_STANDARD 99)

add_library(pruebas_vector.c testing.c testing.h vector.c vector.h)

add_executable(prueba pruebas_vector.c testing.h testing.c vector.h vector.c)