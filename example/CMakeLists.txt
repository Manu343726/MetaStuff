
add_executable(MetaStuffExample main.cpp StringCast.cpp)
target_link_libraries(MetaStuffExample PRIVATE MetaStuff)
target_include_directories(MetaStuffExample PRIVATE nlohmann_json)
