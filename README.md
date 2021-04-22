# Bit Slice

An investigation of bit slice cpu architectures

A cpu architecture is often simplified by dividing it into a series of identical modules known as bitslices. Each module handles a small subset of the cpu word size.

For example a 16-bit machine can be divided into four identical 4-bit slices. 4 bits is a convenient size because many common TTL integrated circuits are based around 4 devices in a package - this includes basic gates, registers, and counters.

Includes a bitslice for the Nand to Tetris "Hack" machine, entirely in 74xx00 2-input Nand Gates.
