cmake_minimum_required (VERSION 3.8)
project (STUDY-CPP CXX)
add_executable(STUDY-CPP main.cpp)
target_compile_features(STUDY-CPP PUBLIC cxx_std_17)
if (MSVC)
	target_compile_options(STUDY-CPP PUBLIC /WX)
endif()

