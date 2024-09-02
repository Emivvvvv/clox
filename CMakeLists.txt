cmake_minimum_required(VERSION 3.28)
project(clox C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(clox
        common.h
        main.c
        memory.h
        memory.c
        chunk.h
        chunk.c
        debug.c
        value.h
        value.c
        vm.h
        vm.c
        compiler.h
        compiler.c
        scanner.h
        scanner.c)
