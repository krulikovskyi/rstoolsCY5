cmake_minimum_required(VERSION 2.4)
project(FPGA-gpiRead)

add_executable(FPGA-gpiRead
main.cpp
alt_fpga_manager.c
globals.c
)
