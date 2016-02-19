# README #

This README would normally document whatever steps are necessary to get your application up and running.

### Requirements ###

* Boost > 1.54
* Armadillo 
* ITK 4.9
* GCC 4.9

### How do I get set up? ###


```
#!bash

mkdir build
cd build
cmake .. -DCMAKE_CXX_COMPILER=/usr/bin/g++-4.9 -DCMAKE_BUILD_TYPE=Release
make
```