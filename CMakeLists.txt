cmake_minimum_required(VERSION 3.13)
project(FunLearningAlgorithmC__)

set(CMAKE_CXX_STANDARD 14)

add_library(FunLearningAlgorithmC__ library.cpp library.h 分治法/BinarySearch.cpp 分治法/MergeSort.cpp 分治法/QuickSort.cpp)