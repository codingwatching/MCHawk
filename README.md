# MCHawk

This is a Minecraft classic server written in C++.

Libraries: SFML, Boost, OpenSSL, and zlib

## Compile

On Linux, install the above libraries with your distribution's package manager

**Arch Linux:**

```
pacman -S gcc make sfml boost openssl zlib
```

**Debian:**

```
apt-get install g++ make libsfml-dev libboost-all-dev libssl-dev libz-dev
```

and then `cd` into the source directory and run

```
make
```

the binary will output to *./bin/Release*

The release version sends a heartbeat to classicube by default. Edit *./bin/Release/config.ini* to change it.
