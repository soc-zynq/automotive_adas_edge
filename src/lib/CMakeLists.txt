# Create a library called "automotive_adas_edge"
add_library(automotive_adas_edge_lib automotive_adas_edge.cpp)

# Specify include directories for the library
target_include_directories(automotive_adas_edge_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
