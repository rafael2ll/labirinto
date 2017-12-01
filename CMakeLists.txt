cmake_minimum_required(VERSION 3.8)
project(Trabalho_Full)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c main.c labirinto.h pilha.h lista.h labSolver.h labSolver.c lista.c pilha.c labirinto.c)
add_executable(Trabalho_Full ${SOURCE_FILES})

target_link_libraries(Trabalho_Full m)