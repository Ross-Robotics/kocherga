cmake_minimum_required(VERSION 3.22)

project(kocherga)

add_library(kocherga INTERFACE)

target_include_directories(kocherga
  INTERFACE
    "kocherga"
)
