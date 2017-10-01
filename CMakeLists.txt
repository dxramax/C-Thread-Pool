cmake_minimum_required(VERSION 3.5.0)
project(c-thread-pool)

SET(SRC_FILES
	thpool.c
	thpool.h
)

ADD_LIBRARY(thpool ${SRC_FILES})

target_link_libraries(thpool ${LIBS})