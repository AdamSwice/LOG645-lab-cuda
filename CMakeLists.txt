cmake_minimum_required(VERSION 3.21)
project(LOG645_cuda CUDA)

set(CMAKE_CUDA_STANDARD 14)

add_executable(LOG645_cuda main.cu)

set_target_properties(LOG645_cuda PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
