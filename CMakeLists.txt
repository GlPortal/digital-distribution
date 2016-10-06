cmake_minimum_required(VERSION 3.0)
project(DigitalDistribution)

set(DigitalDistribution_SOURCES source/DigitalDistribution.cpp)

source_group(Sources ${DigitalDistribution_SOURCES})

add_executable(dd-get ${DigitalDistribution_SOURCES})
