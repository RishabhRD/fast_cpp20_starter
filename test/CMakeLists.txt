add_library(test_main STATIC test_main.cpp)
target_link_libraries(test_main PUBLIC CONAN_PKG::boost-ext-ut)
target_link_libraries(test_main PRIVATE project_options)

# add_executable(tests tests.cpp)
# target_include_directories(tests PRIVATE ../include)
# target_link_libraries(tests PRIVATE project_warnings project_options test_main)
