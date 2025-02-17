# 设置CMake最低版本要求
cmake_minimum_required(VERSION 3.10)

# 设置项目名称
project(hello_world)

# 设置C++标准
set(CMAKE_C_STANDARD 11)

# 指定要编译的源文件
add_executable(hello_world main.c)
