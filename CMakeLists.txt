cmake_minimum_required(VERSION 2.8.12.2 )

project("HelloWorld")
SET(CMAKE_INSTALL_PREFIX "/home1/myproject/project/" FORCE)
add_executable("${PROJECT_NAME}" hello.cpp)

install(TARGETS "${PROJECT_NAME}" DESTINATION bin)
install(FILES "hello.cpp" DESTINATION src)


