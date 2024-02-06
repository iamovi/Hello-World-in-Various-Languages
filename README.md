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

## $ COBOL
```
       IDENTIFICATION DIVISION.
       PROGRAM-ID. HELLO-WORLD.
       PROCEDURE DIVISION.
           DISPLAY 'Hello, World!'.
           STOP RUN.
```
- COBOL, which stands for Common Business-Oriented Language, was first developed in 1959 by a committee led by Grace Hopper.

## $ ALGOL 60
```
BEGIN
    OUTSTRING('Hello World!')
END.
```
- ALGOL was first developed in the late 1950s by a committee of European and American computer scientists.

## $ BASIC
```
10 PRINT "Hello World!"
```
- BASIC (Beginner's All-purpose Symbolic Instruction Code) was first developed in the mid-1960s by John G. Kemeny and Thomas E. Kurtz at Dartmouth College.

## $ APL
```
'Hello World!'
```
- APL (A Programming Language) was developed in the late 1950s and early 1960s by Kenneth E. Iverson.

## $ PL/I
```
HELLO: PROCEDURE OPTIONS(MAIN);
    PUT LIST('Hello World!');
END;
```
- PL/I (Programming Language One) was developed in the late 1960s by IBM.




