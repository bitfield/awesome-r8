# awesome-r8

Resources for the R8 retro CPU architecture.

## Tutorials

A guided introduction to building a high-level R8 emulator can be found here:

* [Welcome to the machine](https://bitfieldconsulting.com/posts/welcome-to-machine)

## Emulators

There are a number of implementations of the R8 in various languages:

* [RX82](https://github.com/bitfield/r8/tree/main/crates/rx82) — a low-level emulator for a retro computer system based on the R8 (Rust)
* [gr8](https://github.com/bitfield/gr8) - a high-level R8 emulator (Go)
* [go-r8](https://github.com/jgrecu/go-r8) — a high-level R8 emulator by Jeremy Grecu (Go)

## Libraries

Software packages of interest to R8 emulator developers:

* [r8cpu](https://github.com/bitfield/r8/blob/main/crates/r8cpu) — core types for R8 emulators, such as registers, flags, and instruction kinds (Rust)

## Tools

Utilities for those writing R8 programs or implementations.

* [r8asm](https://github.com/bitfield/r8/tree/main/crates/r8asm) — an assembler / disassembler for R8

## Testing and validation

Test programs and suites for validating R8 emulators.

* [R8 functional tests](https://github.com/bitfield/r8/tree/main/crates/r8cpu/functional_tests) — a set of individual instruction and function tests, available as binaries and as assembly-language source code

## Books

Books and other published resources on R8:

* _Welcome to the Machine_ (coming soon) — a complete guide to building an R8 emulator, with example code in both Go and Rust
