# i386-Assembly-Hello_World

## How do we run this thing?
---
1. nasm -f elf32 -o hello_world.o hello_world.asm
2. ld -m elf_i386 -o hello_world hello_world.o
3. chmod +x hello_world
4. ./hello_world

