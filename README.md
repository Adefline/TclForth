# TclForth

A multi-platform desktop Forth system based on Tcl/Tk.  It gives you Forth access to a great software universe!

### Overview
TclForth uses Tcl as its native language. The Forth code and colon words are compiled to Tcl procedures that handle arguments and results on a stack. The Forth and Tcl procedures coexist in the Tcl namespace and are all taken care of by the Tcl runtime system. Thus, the Tcl bytecode interpreter is also the inner interpreter of TclForth. For details see http://wiki.tcl.tk/37199.

I have built applications with TclForth for a while and release it as an open source project. The system is prepared as self-contained double-click executables for Windows and OS-X (starpacks) and as a set of source files for Tcl in Linux and elsewhere. Installation = unzip.

Tcl/Tk is a great and much underrated software universe http://www.tcl.tk/about/ .  I don't dream of packing it all into Forth. However, TclForth does provide the usual standard words and some more and the set of Tk words that I have needed so far. And it demonstrates how you can easily add whatever you need. 

### Features

* Universal desktop Forth, runs unchanged in Windows, OS-X, Linux, and more. 
* Native data types array, string, list, and dict.
* Native local variables.
* Native graphical toolkit based on Tk.
* Native database (Metakit).
* Desktop apps for Windows and OS-X

### Guide
The [Wiki](https://github.com/wejgaard/tclforth/wiki) is a good place for the Users Guide. TclForth is special but it all makes sense. And can be experienced interactively.

### Comments 
Use the [Issues](https://github.com/wejgaard/tclforth/issues) for Comments, Questions, Ideas. 


### [Release v0.7.0](https://github.com/wolfwejgaard/tclforth/releases) 

The TclForth.zip archive contains the TclForth source files as well as Tcl executables for Windows and OS-X, and shell code for Linux.

* Windows: Run tclforth.exe
* OS-X: Run tclforth.app
* Linux: Run tclforthx in a terminal. In the Tcl console:

```
    cd <source-directory>
    source tfmain.tcl
```








