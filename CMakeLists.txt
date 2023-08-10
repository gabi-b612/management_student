cmake_minimum_required(VERSION 3.25)
project(management_student C)

set(CMAKE_C_STANDARD 17)

add_executable(management_student main.c etudiant.h etudiant.c)
