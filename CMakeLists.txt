find_package(Boost CONFIG REQUIRED COMPONENTS filesystem)

add_executable(test test.cpp)

target_link_libraries(test Boost::filesystem)

