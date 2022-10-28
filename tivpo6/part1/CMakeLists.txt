cmake_minimum_required(VERSION 3.19)
project(tivpo6)

set(CMAKE_CXX_STANDARD 11)

file(GLOB sources CONFIGURE_DEPENDS "include/*.hpp" "src/*.cpp")
add_executable(tivpo6 ${sources})

include_directories(libs/include)
