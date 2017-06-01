add_executable(multithreaded_echo multithreaded_echo.cpp)
target_include_directories(multithreaded_echo PUBLIC ../src)
target_link_libraries (multithreaded_echo LINK_PUBLIC uWS)
