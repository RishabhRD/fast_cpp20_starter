add_executable(intro main.cpp)
target_include_directories(intro PRIVATE ../include)
target_link_libraries(
  intro
  PRIVATE project_options
          project_warnings)
