cmake_minimum_required(VERSION 3.12)
project(dots VERSION 0.1.0)

option(OVERWRITE_EXISTING_ON_INSTALL "Overwrite existing resource/configuration files diring installation" OFF)
option(INSTALL_SYMBOLIC_LINKS "Install symbolic links intstead of copying the files" ON)
