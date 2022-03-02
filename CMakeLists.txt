cmake_minimum_required(VERSION 3.0)

project(tic_tac_toe)

include_directories(inc)


file(GLOB SRC src/*.cpp)


add_executable(${CMAKE_PROJECT_NAME} ${SRC})

target_link_libraries(${CMAKE_PROJECT_NAME} glfw)
target_link_libraries(${CMAKE_PROJECT_NAME} rt)
target_link_libraries(${CMAKE_PROJECT_NAME} m)
target_link_libraries(${CMAKE_PROJECT_NAME} dl)
target_link_libraries(${CMAKE_PROJECT_NAME} GL)






