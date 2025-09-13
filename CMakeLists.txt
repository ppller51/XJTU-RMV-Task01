cmake_minimum_required(VERSION 3.10)   # CMake 最低版本要求
project(HelloDXRMV)                    # 项目名称

set(CMAKE_CXX_STANDARD 11)             # 使用 C++11 标准
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(hello hello.cpp)        # 生成一个可执行文件 hello
