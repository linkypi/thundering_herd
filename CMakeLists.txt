cmake_minimum_required(VERSION 3.19)
project(thundering_herd C)

set(CMAKE_C_STANDARD 99)

add_executable(thundering_herd main.c epoll_thunder_herd.c)