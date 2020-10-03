# How to Build

#-------------------------------------------------------------
# Linux
#-------------------------------------------------------------
$ mkdir build
$ cd build
$ cmake ..
$ make all

#-------------------------------------------------------------
# Windows(cmake + MinGW)
#-------------------------------------------------------------
$ mkdir build
$ cd build
$ cmake .. -G "MinGW Makefiles"
$ mingw32-make.exe all

// For specific project
$ mingw32-make playground
