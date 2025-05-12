cmake_minimum_required(VERSION 2.4)
project(FPGA-resetFabric)
add_executable(FPGA-resetFabric
main.cpp
alt_fpga_manager.c
globals.c
)
