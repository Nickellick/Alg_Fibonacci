cmake_minimum_required(VERSION 3.14)
project(Alg_Fibonacci C)

set(CMAKE_C_STANDARD 11)

add_executable(Alg_Fibonacci main.c)
target_link_libraries(Alg_Fibonacci m quadmath)