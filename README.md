# Simple "Hello World!" written in x86 Assembly
1. Compile using nasm:
```
nasm -f elf32 -o hello_world.o hello_world.asm
```
2. Create executable from object:
```
ld -m elf_i386 -o hello_world hello_world.o
```
3. Run the executable:
```
./hello_world
```
