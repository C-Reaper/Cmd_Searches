# Project README

## Overview
The project is a simple C program that demonstrates the use of an array data structure. It supports multiple platforms and build configurations including Linux, Windows using Wine, and WebAssembly for web execution.

## Features
- Dynamic array creation
- Setting values in the array by index names
- Sorting the array using insertion sort

## Project Structure
### Prerequisites
- C/C++ Compiler (GCC)
- Make utility
- Standard development tools

## Build & Run
To build and run the project, follow these steps:

1. **Build for Linux:**
   ```sh
   cd /path/to/project
   make -f Makefile.linux all
   make -f Makefile.linux exe
   ```

2. **Build for Windows (using Wine):**
   ```sh
   cd /path/to/project
   make -f Makefile.wine alldebug
   make -f Makefile.wine debug
   ```

3. **Build for WebAssembly:**
   ```sh
   cd /path/to/project
   make -f Makefile.web all
   make -f Makefile.web exe
   ```

These commands will compile the code using the respective Makefiles and execute the resulting binary or WASM file.