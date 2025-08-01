# Build the project

## Requirements
- CMake 3.12+
- C++ compiler (GCC, Clang or MSVC)

## Linux/macOS
``` bash
mkdir build && cd build
make ..
make
```

## Windows (Visual Studio)
``` bash
mkdir build
cd build
cmake -G "Visual Studio 17 2022" ..
cmake --build. --config Release
```

## Run
``` bash
./build/memory_tool # or Memory_tool.exe on Windows
```
