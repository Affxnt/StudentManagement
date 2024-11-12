cmake_minimum_required(VERSION 3.29)
project(COMP348_A1 C)

set(CMAKE_C_STANDARD 11)

add_executable(COMP348_A1 main.c
        data.h
        student.h
        data.c
        calc.h
        calc.c
        ordering.h
        ordering.c
        spreadsheet.h
        spreadsheet.c)
