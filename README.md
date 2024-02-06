# RISC-V bare metal "fake BIOS" example

This code is meant to accompany the website article: https://popovicu.com/posts/bare-metal-programming-risc-v/

Compile: `make hello CROSS_COMPILE=riscv64-unknown-elf-`

To build the "fake BIOS", simply run `make hello` (you may want to change your cross compile make prefix with `CROSS_COMPILE`).

Run with QEMU: `qemu-system-riscv64 -machine virt -bios hello`
