cmake_minimum_required(VERSION 3.1 FATAL_ERROR)

set(SOURCES
    QuadCopterShiftAvoidance.cc
    QuadCopterVFFAvoidance.cc
    QuadCopterStopAvoidance.cc)

add_library(avoidance OBJECT ${SOURCES})
