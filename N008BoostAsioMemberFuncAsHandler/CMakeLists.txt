cmake_minimum_required(VERSION 3.10)
project(N008BoostAsioMemberFuncAsHandler)

set(CMAKE_CXX_STANDARD 17)

link_libraries(
        boost_system
)

add_executable(N008BoostAsioMemberFuncAsHandler main.cpp)