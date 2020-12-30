cmake_minimum_required (VERSION 2.8.11)

set(CONFIG_HHAL_GN true)
set(CMAKE_INSTALL_PREFIX "/opt/mango/usr")

add_subdirectory (bin)
add_subdirectory (include)
add_subdirectory (src)
