find_package(imgui REQUIRED)

ADD_EXECUTABLE(TinyRender main.cpp)

target_link_libraries(TinyRender imgui)