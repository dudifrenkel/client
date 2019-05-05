cmake_minimum_required(VERSION 3.13)
project(client)

set(CMAKE_CXX_STANDARD 14)
#link_libraries(ws2_32 wsock32)
link_libraries(Ws2_32)
link_libraries(Mswsock)
link_libraries(AdvApi32)
add_executable(client main.cpp)