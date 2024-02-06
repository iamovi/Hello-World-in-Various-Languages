### Hello World in Various Programming Languages.


## $ binary
```
01001000 01100101 01101100 01101100 01101111 00101100 00100000 01010111 01101111 01110010 01101100 01100100 00100001
```
- Developed in the mid-20th century.

## $ assembly
```
section .data
    hello db 'Hello World!',0

section .text
    global _start

_start:
    ; write Hello, World! to stdout
    mov eax, 4          ; syscall number for sys_write
    mov ebx, 1          ; file descriptor 1 (stdout)
    mov ecx, hello      ; pointer to the string
    mov edx, 13         ; length of the string
    int 0x80            ; call kernel

    ; exit program
    mov eax, 1          ; syscall number for sys_exit
    xor ebx, ebx        ; exit code 0
    int 0x80            ; call kernel
```
- Assembly language emerged in the late 1940s and early 1950s alongside the development of the earliest computers.

## $ fortran
```
program HelloWorld
    print *, 'Hello World!'
end program HelloWorld
```
- Fortran, which stands for Formula Translation, was first released in 1957 by IBM.

## $ lisp
```
(format t "Hello World!")
```
- Lisp was first developed in 1958 by John McCarthy at the Massachusetts Institute of Technology (MIT).

