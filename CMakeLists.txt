cmake_minimum_required(VERSION 3.24)
project(POO_porject)

set(CMAKE_CXX_STANDARD 17)

add_executable(POO_porject main.cpp Cell.cpp Cell.h GetCell.cpp GetCell.h Global.cpp Global.h DrewText.cpp DrewText.h Field.cpp Field.h)


set(SFML_DIR "C:/SFML-2.5.1/lib/cmake/SFML")
target_link_libraries(POO_porject sfml-graphics sfml-audio)

