cmake_minimum_required(VERSION 2.4)
project(FPGA-readMSEL)
add_executable(FPGA-readMSEL 
main.cpp
alt_fpga_manager.c
globals.c
)
