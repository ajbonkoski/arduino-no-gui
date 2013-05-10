#Arduino without GUI

This project basically exists to showcase the Makefile. There are a few setup steps:

* You need to install the Arduino build tools and adjust the Makefile to point to them on your system.
* You need to ensure that the Makefile specifies the correct Arduino model.

Then, to build the enclosed LED-blinking demo:

    make
    
To install that over USB to an Arduino Uno (no others have been tested):

    make download
    
