# sds011lib
ESP32 C/C++ Arduino library for the Nova Fitness SDS011 PM2.5 dust sensor

**WARNING: CODE IS CURRENTLY UNDER DEVELOPMENT AND UNFINISHED AND UNTESTED**

## Installation and Usage

Check out repository 

    git clone https://github.com/buddemat/sds011lib.git  

Basic usage: include the library in your code, initialize it and 

    #include <sds011lib.h>

## Documentation
The documentation for this library is annotated directly in the source files and can be generated using [Doxygen](https://www.doxygen.nl/index.html):

    doxygen

As configured in the `Doxygen` file, a folder `./doxydoc` will be created.
In this folder will be two subfolders `html` and `latex`.
To view the documentation, you can e.g. open the file `index.html` in the `html` folder.

## Known Issues
The library is not yet completely implemented. 

Missing functionality includes (this and maybe more):

* energy saving mode (sleep/wakeup) not yet tested
* timed hibernate (cycle to work) not yet implemented
* setting user ID not yet implemented
* version number query not yet implemented 
* no `.ino` example sketch yet
