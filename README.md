# Palindrome Checker with Pointers

A C program that checks if a given string is a palindrome, ignoring spaces. The program uses pointer manipulation for
efficient string traversal.

## Description

This program implements a palindrome checker that:

- Uses pointer arithmetic to traverse the string
- Ignores spaces while checking
- Works with any string input
- Provides clear output indicating if the string is a palindrome or not

## Building

Follow these steps to build the project:

### Method 1: Cloning the Build Method in CLion

1. Open CLion and import the project.
2. Go to the "File" tab and select "New Project from Version Control".
4. Follow the CLion wizard instructions to clone the [repository](https://github.com/federicomaniglio/MANIGLIO_palindromo_puntatori.git)

### Method 2: Manual Build with CMake

1. Create a build directory:
   ```bash
   mkdir build
   cd build
   ```

2. Generate build files:
   ```bash
   cmake ..
   ```

3. Build the project:
   ```bash 
   cmake --build .
   ```
