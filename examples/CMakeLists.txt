
add_library(common-clip STATIC common-clip.cpp)
target_link_libraries(common-clip PRIVATE ggml)
target_include_directories(common-clip PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

# add_executable(main main.cpp)
# target_link_libraries(main PRIVATE clip common-clip ggml)

# add_executable(zsl zsl.cpp)
# target_link_libraries(zsl PRIVATE clip common-clip ggml)
