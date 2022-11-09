# C++ Print!

A beginner's Best Friend to save time print a basic text to output!!!

[![github-license](https://img.shi
elds.io/github/license/SUFandom/print-cpp?style=flat&logo=github)](https://github.com/SUFandom/print-cpp)

The `main.cpp` is a vivid example of how to use, and Access the library. The 'Libraries' are located in `lib` Directory.

## How to import it to your work

First, we need to understand what `Headers
 .h` are!

 Headers are basically a container-like script to actually making your `main.c` or `main.cpp` if you're in C++. its purpose is to make sure that a larger a project gets, your code will be organized like a charm.

 For example, what you see in myheader.h:

```
#pragma once
#define YOOOO 1;
```

*Note : Pragma is an alt of #ifndef*


What you see in main.cpp

```
#include <iostream>
#include <stdio.h>
#include "myheader.h"

```

What the clang and g++ Sees:

```

#include <iostream>
#include <stdio.h>
#define YOOOO 1

```

Yeah its like an external Container!

And its helpful if you're working in a large project!

You can import the works like in the `main.cpp` example. and try it!