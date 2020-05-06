# M Programming Language Specification
M is a multi-paradigm programming language that can be both statically typed and dynamically typed.  It's main goal is to be as high level as possible, while still having little restrictions.

## Coding Example
A quick example of a simple M program could look like this:
```
function main(argc, args) {
    Log("Hello, world!");

    return 0;
}
```
It outputs `Hello, world!` to the console and returns an error code of `0`. (No error)

## Basic Syntax
### Variables
*Definition*
```
[public|private|static|const] [type] <iden> [= [value]];
```
*Blank definition* <br>
Blank definition is when you define a variable without a value.  For example:
```
String v;
```
Then it can be defined later:
```
v = "Hello, world!";
```
Changing the value of a non-blank variable is the same.
### Functions
*Definition*
```
function <iden>([args]) {
    /* ... */
}
```
*Execution*
```
<iden>([args]);
```