# i386-Assembly-Hello_World

- just wanted to test out assembly a bit so here is hello world in x86 32-bit assembly!\
![image](https://user-images.githubusercontent.com/86436966/136079222-5a750c3c-81f9-4ab6-ac87-46ca9577cad8.png)

## How do we run this thing?
1. nasm -f elf32 -o hello_world.o hello_world.asm
2. ld -m elf_i386 -o hello_world hello_world.o
3. chmod +x hello_world
4. ./hello_world

  ![image](https://user-images.githubusercontent.com/86436966/136079123-12bc5253-eb15-4e11-9798-af0983374b5b.png)
