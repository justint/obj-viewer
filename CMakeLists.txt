cmake_minimum_required(VERSION 3.2)
project(obj-viewer)

set(CMAKE_CXX_STANDARD 14)

find_package(OpenGL REQUIRED)
find_package(GLUT REQUIRED)

set(SOURCE_FILES obj-viewer.cpp)
add_executable(obj-viewer ${SOURCE_FILES})
include_directories(${OPENGL_INCLUDE_DIRS}  ${GLUT_INCLUDE_DIRS})

target_link_libraries(obj-viewer ${OPENGL_LIBRARIES} ${GLUT_LIBRARY})
target_compile_options(obj-viewer PUBLIC -Wno-deprecated-declarations)
