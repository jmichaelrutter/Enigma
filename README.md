Enigma

This doesn't work in Eclipse because of buffer issues, so I just use the command prompt to compile.

1. Download encode.c and put it in a folder.
2. Google how to add MinGW\bin to your PATH environment variable.
2. Open command prompt and navigate to that folder using "cd"
3. gcc encode.c -o encode.exe
4. encode.exe

The first algorithm just adds 1 to each character, and the last character is set to the first character in the group

The second algorithm splits the group of characters in half swtiches the position of the first and second halves.  Plus the special characters are swapped with some numbers and vice versa.
