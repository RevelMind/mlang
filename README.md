# M Programming Language Specification
- [Chapter 1: Introduction](#chapter-1-introduction)
- - [1.1: Layout](#11-layout)
- - [1.2: Example Application](#12-example-application)

## Chapter 1: Introduction 
M is a programming language inspired by Lua, Objective-C, C++ and JavaScript.  It's main goal is to be as high level as possible, while having minimal restrictions and a large library base to help with all sorts of applications.

The M programming language is both statically and dynamically typed.  You can incorporate whichever programming characteristic seamlessly with no extra lines of code.

### 1.1: Layout
> We'll get back here once more sections are added.

### 1.2: Example Application
The simplest form of application would be this:
```
function main(argc, args) {
    Log("Hello, world!");

    return 0;
}
```
This application outputs
```
Hello, world!
```
then returns an error code of 0 (no error) and exits.

## Chapter 2: 