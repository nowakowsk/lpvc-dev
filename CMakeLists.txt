cmake_minimum_required(VERSION 3.14)

project(long-play-video-codec)

add_subdirectory(liblpvc)

if(WIN32)
  add_subdirectory(lpvc-vfw)
endif()
