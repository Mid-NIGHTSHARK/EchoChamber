cmake_minimum_required(VERSION 4.4.3)

find_package(raylib)
add_executable(game
    src/game.cpp
)
target_link_libraries(game PRIVATE raylib)

