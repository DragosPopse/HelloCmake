cmake_minimum_required(VERSION "3.17.0")

project("HelloCmake")

add_executable("${PROJECT_NAME}" "Main.cpp")

install(TARGETS "${PROJECT_NAME}" DESTINATION bin)
install(TARGETS "Main.cpp" DESTINATION src)