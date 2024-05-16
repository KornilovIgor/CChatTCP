cmake_minimum_required(VERSION 3.22)

set(CMAKE_CXX_STANDARD 17)

set(PROJECT_NAME CChatCli)
project(${PROJECT_NAME})

file(GLOB CPPS "src/*.cpp")

include_directories("${PROJECT_SOURCE_DIR}/include")

add_executable(${PROJECT_NAME} ${CPPS})