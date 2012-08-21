Or1ksim
=======

Or1ksim is a generic OpenRISC 1000 architecture simulator capable of emulating
OpenRISC based computer systems at the instruction level. It includes models
of a range of peripherals, allowing complete systems to be modelled.

For full details see http://opencores.org/or1k/Or1ksim

Installation
------------

Or1ksim uses a standard GNU autoconf/automake installation and is designed to
be built in a separate build directory. So from the main directory, a minimal
install can be done with

    mkdir bd
    cd bd
    ../configure
    make
    sudo make install

Full details on installation are provided in the user manual, in the *doc*
directory.


Jeremy Bennett <jeremy.bennett@embecosm.com>
21 August 2012
