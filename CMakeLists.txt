# Convience project for the lazy who want to copy this ZIP over.
# Provides:
#   PYTHON27_STD_ZIP - a path to the python27.zip lib
#   PYTHON27_STD_ZIP_DIR  - a path to the directory of python27.zip
cmake_minimum_required(VERSION 3.1)

project(Python27StdLib)

set(PYTHON27_STD_ZIP ${PROJECT_SOURCE_DIR}/python27.zip PARENT_SCOPE)
set(PYTHON27_STD_ZIP_DIR ${PROJECT_SOURCE_DIR} PARENT_SCOPE)
