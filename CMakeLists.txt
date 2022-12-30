cmake_minimum_required(VERSION 3.15)
project(RayTracingDemo)

set(CMAKE_CXX_STANDARD 17)

add_executable(RayTracingDemo Test.cpp)

target_link_libraries(RayTracingDemo ${TORCH_LIBRARIES})

