cmake_minimum_required(VERSION 3.25)

project(ZodiaxMod LANGUAGES CXX)

find_package(Geode REQUIRED)

add_geode_mod(
    com.human.zodiax
    VERSION v1.0.0
    SOURCES main.cpp
)
