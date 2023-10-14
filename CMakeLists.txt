cmake_minimum_required
project (STUDY-CPP CXX)
add_executable(STUDY-CPP main.cpp)
target_compile_features(STUDY-CPP PUBLC cxx_std_17)
if (MSVC)
target_compile_options(STUDY-CPP PUBLIC /WX)

