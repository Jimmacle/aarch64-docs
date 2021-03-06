# aarch64-docs

The purpose of this repo is to collect and organize notes and other reference information related to writing and debugging ARM64 assembly, particularly under Linux on a Raspberry Pi 4.

## See also
These are links to official documentation sources.
* [ARMv8-A Architecture Reference](https://developer.arm.com/documentation/ddi0487/gb/): Detailed technical documentation about how ARM works and all available instructions
* [ARM64 Linux Syscalls](https://arm64.syscall.sh/): Kernel functions available to invoke via a supervisor call `svc 0`
* [Procedure Call Standard](https://github.com/ARM-software/abi-aa/blob/main/aapcs64/aapcs64.rst): Standards for interfacing with external code
* [GNU Assembler](https://sourceware.org/binutils/docs/as.html): How to use `as` and write syntax beyond the base ARM64 instruction set
* [GDB](https://visualgdb.com/gdbreference/commands/): GDB command reference
* [GEF](https://gef.readthedocs.io/en/latest/): GDB Extended Features documentation
