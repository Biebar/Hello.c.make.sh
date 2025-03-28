# Hello.c.make.sh

This is a Hello World program written in C.

## Usage

Simply use `bash main.c` to build and run.

## Building

A Makefile named `main.c` is provided with this program. You can build with
```
make -f main.c build
```
Additional compilation options can be provided by setting the `b` and `c` variables on the command line :
```
make b=Dendif= c="DHello=hello" -f main.c build
```

## Dependencies

 - Bash
 - GNU Make
 - gcc
