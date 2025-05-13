# Black-Scholes Option Pricer

A simple C++ implementation of the Black-Scholes formula for pricing European call and put options.

## Features
- European call and put pricing
- Modular design (headers, source, tests)
- CLI-based interface
- Easily extendable for Greeks, implied volatility, etc.

## Build Instructions

Using CMake:
```bash
mkdir build
cd build
cmake ..
make
./black_scholes
