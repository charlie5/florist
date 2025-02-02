# FLORIST

This directory contains the components of FLORIST, an
implementation of the IEEE Standards 1003.5: 1992, IEEE STD
1003.5b: 1996, and parts of IEEE STD 1003.5c: 1998, also known as
the POSIX Ada Bindings.

## NORMAL INSTALLATION:

Follow the steps described in the INSTALL file.

## COMPILING YOUR PROGRAMS WITH FLORIST:

To compile your own programs with Florist, you will need to
add a "with florist" in your project file. florist.gpr can be found
under prefix/lib/gnat is also sufficient.

Alternatively, to use Florist without project files, you can also
do something like:

$ gnatmake -I/prefix/floristlib main -largs -lflorist

## Using Alire

In your own [Alire](https://alire.ada.dev) project, add Florist dependency:

`% alr with florist`

Then you can import the Ada Florist packages in your programs.
