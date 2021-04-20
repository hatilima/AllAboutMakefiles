# AllAboutMakefiles
1. Show terminal compilation for simple main.c to main.exe.
2. Then try a main.c and a plus.c compiled seperately and then linked to main.exe. The main.c uses an addition function from plus.c by including plus.c. Also show that the main.c cannot be compiled to the end from main.c to main.o and then to main.exe alone because it needs plus.c.
3. Split plus.c into plus.c and plus.h. This will be to show that when the functional implementation of add function changes, main.o will not require to be rebuilt...only plus.o will be rebuilt and then linked to the old main.o to make main.exe.
4. With this increase in number of files and remembering which ones need/don't need rebuilding, show the importance of make. Start with the basic rigid make without pattern rules. Without multiple folders.
5. Then add variables like CC, CFLAGS, etc
6. Then add scr and build folders
7. Then make the Makefile more generic with pattern rules and wildcards
8. Then finally try to implement everything on a more complex project like an ARM Cortex-M project with startup code, linker script, some register defines and main user code.

Each of the numbers will be a folder, one being a development on the previous one.
