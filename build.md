# Build
Please use CMake to build.


```
mkdir build
cmake -DCMAKE_CXX_COMPILER=clang++ -DCMAKE_C_COMPILER=clang ..
make -j4
```


This software builds heavily on the C++11 standard.
At the time of development, llvm/clang >= 3.4 was required for building.
At this time, other compilers may have implemented more complete support
for the standard.
