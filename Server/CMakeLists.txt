cmake_minimum_required(VERSION 3.20)
project(JHKServer)

set(CMAKE_CXX_STANDARD 20)

add_executable(JHKServer main.cpp src/Server.cpp src/Server.hpp src/LinuxServer/LinuxServer.cpp src/LinuxServer/LinuxServer.hpp src/WindowsServer/WindowsServer.cpp src/WindowsServer/WindowsServer.hpp)
