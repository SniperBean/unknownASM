# I don't know why there's a snippet of assembly language, so I decided to push it to pornhu...uh... I mean github
- nasm -f macho64 -o helloworld.o hello_world.asm
- ld -o helloworld -e _main helloworld.o -macosx_version_min 10.13 -lSystem
- ./helloworld
