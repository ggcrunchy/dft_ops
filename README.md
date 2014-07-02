dft_ops
=======

Submodule containing various discrete Fourier transforms (with a focus on 1D and 2D FFT's).

**STATUS**
==========

This is more or less functional, though the comments and docs could stand some improvement.

Future possibilities include N-D transforms (> 2), power spectra, non-POT transforms (via Winograd, Bluestein, etc.).

**DEPENDENCIES**
================

Tested on Lua 5.1. (Some tests [here](https://github.com/ggcrunchy/Strays/blob/master/Unit%20Tests/convolve.lua).)