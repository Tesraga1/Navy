cmake_minimum_required(VERSION 3.1)
project(Navy_Knights_Dogo_V1)


add_library(${PROJECT_NAME} src/main.cpp src/autons.cpp src/EZ-Template/auton_drive_functions.cpp src/EZ-Template/joystick_control.cpp src/EZ-Template/setup.cpp src/EZ-Template/util.cpp src/lift.cpp src/mogo.cpp src/tilter.cpp src/puttputt.cpp include/puttputt.h src/intake.cpp include/intake.h)
target_include_directories(${PROJECT_NAME} PUBLIC include)