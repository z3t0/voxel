cmake_minimum_required (VERSION 2.6)
project(voxel)

set(SOURCES
  src/main.c
  )

add_executable(${PROJECT_NAME} ${SOURCES}) 
