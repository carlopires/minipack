minipack
========

The minipack library provides a simple interface for reading and writing
MessagePack data. It does not provide any containers or buffer management.
It just provides callbacks for reading and writing values in MessagePack
format to memory.

To use minipack, simply include the source and header files in your program.

Compilling
----------
    
    make
    

Running tests
-------------

To run the tests you need to have installed [msgpack-c](https://github.com/msgpack/msgpack-c.git) and [ruby language](http://ruby-lang.org). If you are in a Debian based environment (Linux) these will be installed automatically. With these in mind just do
    
    make test
    
