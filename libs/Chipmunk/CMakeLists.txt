PROJECT(CHIPMUNK)

SET(CMAKE_C_FLAGS_RELEASE "-O3 -ffast-math -std=gnu99")

SUBDIRS(src Demo)

SET (CMAKE_BUILD_TYPE Release)
