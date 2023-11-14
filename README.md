# CPP-Utilities
This repo contains useful C++ utilities I have created/adopted that has made my life easier and hopefully will make yours too 💪


## Contents
-- Table here

## timer.h
a simple timer that can be used to get the wall clock time for operations in your program


**Usage:**
First import the timer into your program. Then create the timer object, which starts the timer. Once you want to end the timer, call the object's _getTime()_ method.
```cpp
#include "timer.h"
...

timer time; // starts the timer
...
double final_time = time.getTime(); // returns the execution time
...
```
