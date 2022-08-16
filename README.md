# soundtracker

this project has been forked in order to ensure the continued maintenance of soundtracker, and to improve it with quality of life improvements.

this is an old chiptune composition tool that I made as my first program back in 2014 (excluding the tutorials).

this tool emulates/implements a fictitious soundchip that I thought of years ago, with heavy inspiration from the 8-bit era soundchips (like the SID).

# and what is this "ssinter" thing?

ssinter is an interpreter for the soundchip dump format. check [ssformat.md](papers/ssformat.md) for more information.

# build instructions

the only available build instructions are for linux. if you have built it on another OS, please open a pull request with instructions on how to build on that platform and it will be added.

## linux build instructions

on your distro you'll need CMake, Git and a C++ compiler.
run the following commands:
```
mkdir build
cd build
cmake ..
make
```
enjoy your newly built binary of soundtracker! :)

# notes

this project uses blip-buf, which is under the same license.
