# 010 Editor KeyGen

A License Key generator for [010 Editor](http://www.sweetscape.com/download/010editor/).
Written purely in Assembly

## Warning

It is for **EDUCATIONAL PURPOSES** only.

## Features

1. Arbitrary usernames are supported

2. License expiration date can be customized (any date between the next day and December 31, 3000)

3. N-User License Keys can be generated where 1 &le; N &le; 1000

You **DON'T NEED MSVCRT** to run this program

## Assembling

### Pre-Requisites
- Windows
- [Flat Assembler](http://flatassembler.net/download.php)

### Building

 1. Clone the repository somewhere.
 2. Copy `include\win32ax.inc` from the flat assembler directory to the repository.  
    You should now have `main.asm` and `include/win32ax.inc` in the same directory.
 3. Open a terminal in the repository root and run `fasm main.asm`.  
    You will now have `main.exe`.


## Screenshot

![Screenshot](screenshot.gif)

## License

[MIT](/LICENSE)
