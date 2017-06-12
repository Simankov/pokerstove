project(eval)

add_executable(ps-colex main.cpp)
add_definitions ("-Wall -std=c++0x")

target_link_libraries(ps-colex
        peval
        ${Boost_LIBRARIES}
)
