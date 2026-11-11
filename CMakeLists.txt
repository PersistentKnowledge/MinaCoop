cmake_minimum_required(VERSION 3.20)
project(mth_coop)

add_library(mth_coop SHARED src/library.cpp)
set_target_properties(mth-coop PROPERTIES OUTPUT_NAME "mod")