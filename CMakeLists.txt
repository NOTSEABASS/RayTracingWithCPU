cmake_minimum_required(VERSION 3.15)
project(RayTracingDemo)

set(CMAKE_CXX_STANDARD 17)

# message("${TORCH_LIBRARIES}")
# message("${TORCH_INCLUDE_DIRS}")

add_executable(RayTracingDemo Test.cpp)

target_link_libraries(RayTracingDemo ${TORCH_LIBRARIES})


# link_directories(
#     "D:/Python/Lib/site-packages/torch/lib"
# )
# target_link_libraries(libtorchDemo 
#     "D:/Python/Lib/site-packages/torch/lib/c10.lib"
#     "D:/Python/Lib/site-packages/torch/lib/c10_cuda.lib"
#     "D:/Python/Lib/site-packages/torch/lib/torch.lib"
#     "D:/Python/Lib/site-packages/torch/lib/torch_cuda.lib"
#     "D:/Python/Lib/site-packages/torch/lib/torch_cpu.lib"
#     )
# target_include_directories(libtorchDemo
# PRIVATE 
#     "D:/Python/Lib/site-packages/torch/include/torch/csrc/api/include"
#     "D:/Python/Lib/site-packages/torch/include" 
#     )
