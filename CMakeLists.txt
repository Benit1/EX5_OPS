cmake_minimum_required(VERSION 3.23)
project(EX5_OPS C)

set(CMAKE_C_STANDARD 99)

add_executable(EX5_OPS main.c Prime.c threadsQueue.c Queue.h ActiveObject.c ActiveObject.h st_pipeline.c st_pipeline.h)
