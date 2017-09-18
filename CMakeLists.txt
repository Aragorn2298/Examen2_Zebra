cmake_minimum_required(VERSION 3.7)
project(Examen2_Zebra)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Evaluador.cpp Evaluador.h Libro.cpp Libro.h NodoBinario.cpp NodoBinario.h)
add_executable(Examen2_Zebra ${SOURCE_FILES})