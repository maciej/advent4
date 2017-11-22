cmake_minimum_required(VERSION 3.8)
project(advent4)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        advcave.h
        advdec.h
        advdef.h
        advent.c
        advent.h
        advent1.h
        advent2.h
        advent3.h
        advent4.h
        advword.h
        database.c
        english.c
        itverb.c
        proto.h
        turn.c
        verb.c)

add_executable(advent4 ${SOURCE_FILES})
