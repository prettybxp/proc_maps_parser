

cmake_minimum_required(VERSION 2.6)
project(pmparser)


add_library(pmparser pmparser.c)


install(
    TARGETS pmparser
    LIBRARY DESTINATION lib
    ARCHIVE DESTINATION lib
)

install(
    FILES pmparser.h
    DESTINATION include
)



