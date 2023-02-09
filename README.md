
# TEMPLATE PROJECT

- A directory sample for single c/cpp projcet which build with CMake.
- Just copy and pasted to setup my project.

## What's the output type?

||Unix|Windows|
|--|--|--|
|RUNTIME|executable| `.exe`,`.dll`|
|LIBRARY|.so||
|ARCHIVE|.a|`.a`,`.lib`(contained the dll link info/stub)|

## Current issues

- The win32 build system may not recongnize the `CMAKE_BUILD_TYPE`, instead take something likes `CONFIGURE_TYPE` as the parameter of that.   

- Currently let it make error and exit. will fix this later...
