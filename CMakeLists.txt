cmake_minimum_required (VERSION 2.6)

project(osx-elf-header LANGUAGES C)

add_library(osx-elf-header include/elf.h)
target_include_directories(osx-elf-header PUBLIC include/)