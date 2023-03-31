cmake_minimum_required(VERSION 3.12.4)

#forked library is available at git@github.com:hptechdesign/rs-232.git
add_library(rs232  rs232.c)
target_include_directories(rs232 PUBLIC .)