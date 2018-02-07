# Eurobit
The digital counterpart of the Euro.

## Eurobit compile guide

If your on ubuntu, just download depenencies and compile by doing

> make

If your getting an error around the rocksdb part of the compile, do this:

> cd external
> cd rocksdb
> cd build_tools
> chmod 755 build_detect_platform

Then retry the compile

If your on windows, just download a binary, its not worth the hassle of compiling from source :(
