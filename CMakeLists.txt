CMAKE_MINIMUM_REQUIRED(VERSION 2.6.0)
PROJECT(NV)

SET(NV_CMAKE_DIR "${NV_SOURCE_DIR}/cmake")
SET(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${NV_CMAKE_DIR}")

ADD_SUBDIRECTORY(src)

