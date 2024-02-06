![project-preview-image](https://ik.imagekit.io/iamovi/oviproject-preview.gif?updatedAt=1707222111761)

## $ binary
```
01001000 01100101 01101100 01101100 01101111 00101100 00100000 01010111 01101111 01110010 01101100 01100100 00100001
```
- Binary is a base-2 number system, developed in the mid-20th century.

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

## $ simula
```
begin
    OutText("Hello World!");
    OutImage;
end;
```
- Simula, developed in the 1960s by Ole-Johan Dahl and Kristen Nygaard at the Norwegian Computing Center, is considered one of the earliest object-oriented programming languages.

## $ pascal
```
program HelloWorld;
begin
    writeln('Hello World!');
end.
```
- Pascal was developed in 1970 by Niklaus Wirth.

## $ C
```
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```
- C was developed in the early 1970s by Dennis Ritchie at Bell Labs.

## $ smalltalk
```
Transcript show: 'Hello, World!'; cr.
```
- Smalltalk was developed in the early 1970s by Alan Kay, Dan Ingalls, Adele Goldberg, and others at Xerox PARC.

## $ ada
```
with Ada.Text_IO;

procedure Hello is
begin
    Ada.Text_IO.Put_Line("Hello, World!");
end Hello;
```
- Ada was developed in the late 1970s and early 1980s by a team led by Jean Ichbiah at CII Honeywell Bull.

## $ prolog
```
hello_world :-
    write('Hello World!').
```
- Prolog was developed in the early 1970s by Alain Colmerauer and Philippe Roussel.

## $ forth
```
: HELLO ." Hello World!" ;
HELLO
```
- Forth was developed in the late 1960s and early 1970s by Charles H. Moore.

## $ tcl
```
puts "Hello, World!"
```
- Tcl (Tool Command Language) was created in the late 1980s by John Ousterhout.

## $ perl
```
print "Hello, World!\n";
```
- Perl was developed in the late 1980s by Larry Wall.

## $ lua
```
print("Hello, World!")
```
- Lua was developed in the early 1990s by Roberto Ierusalimschy, Luiz Henrique de Figueiredo, and Waldemar Celes.

## $ C++
```
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```
- C++ was developed in the early 1980s by Bjarne Stroustrup at Bell Labs.

## $ C#
```
using System;

class HelloWorld
{
    static void Main()
    {
        Console.WriteLine("Hello World!");
    }
}
```
- C# was first released in December 2000 as part of the .NET Framework by Microsoft.

## $ java
```
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
- Java was developed in the mid-1990s by James Gosling and his team at Sun Microsystems.

## $ Python
```
print("Hello World!")
```
- Python was created in the late 1980s by Guido van Rossum.

## $ JavaScript
```
console.log("Hello World!");
```
- JavaScript was developed in the mid-1990s by Brendan Eich at Netscape Communications Corporation.

## $ ruby
```
puts "Hello World!"
```
- Ruby was developed in the mid-1990s by Yukihiro Matsumoto (Matz).

## $ PHP
```
<?php
echo "Hello World!";
?>
```
- PHP was created in the mid-1990s by Rasmus Lerdorf.

## $ swift
```
print("Hello World!")
```
- Swift was developed by Apple Inc. and introduced in 2014.

## $ SQL
```
SELECT 'Hello World!';
```
- SQL (Structured Query Language) is not typically used to directly output "Hello, World!" messages, as it's primarily a language for querying and manipulating databases. However, you can print a message using SQL in some database systems like PostgreSQL.

SQL was developed in the early 1970s by Donald D. Chamberlin and Raymond F. Boyce at IBM.

## $ kotlin
```
fun main() {
    println("Hello, World!")
}
```
- Kotlin was developed by JetBrains and introduced in 2011.

## $ TypeScript
```
console.log("Hello World!");
```
- TypeScript, developed by Microsoft, was first released in 2012.

## $ R
```
cat("Hello World!\n")
```
- R, a language and environment for statistical computing and graphics, was developed in the early 1990s by Ross Ihaka and Robert Gentleman.

## $ MATLAB
```
disp('Hello World!');
```
- MATLAB (Matrix Laboratory) was developed in the late 1970s by Cleve Moler at the University of New Mexico.

## $ Objective-C
```
#import <Foundation/Foundation.h>

int main() {
    NSLog(@"Hello World!");
    return 0;
}
```
- Objective-C was developed in the early 1980s by Brad Cox and Tom Love.

## $Groovy
```
println "Hello World!"
```
- Groovy, a dynamic language for the Java Virtual Machine (JVM), was created in the early 2000s by James Strachan and Bob McWhirter.

## $ dart
```
void main() {
  print('Hello World!');
}
```
- Dart, developed by Google, was introduced in 2011.

## $ scala
```
object HelloWorld {
  def main(args: Array[String]): Unit = {
    println("Hello World!")
  }
}
```
- Scala, a general-purpose programming language, was created by Martin Odersky and first released in 2003.

## $ shell scripting language (e.g., Bash)
```
#!/bin/bash
echo "Hello World!"
```
- Shell scripting languages, such as Bash, are used for automating tasks and executing commands in Unix-like operating systems.

## $ VHDL
```
library ieee;
use ieee.std_logic_1164.all;
use ieee.std_logic_textio.all;
use std.textio.all;

entity HelloWorld is
end entity;

architecture Behavioral of HelloWorld is
begin
    process
    begin
        write(output, string'("Hello World!"));
        writeline(output);
        wait;
    end process;
end architecture;
```
- VHDL (VHSIC Hardware Description Language) was developed in the early 1980s by the U.S. Department of Defense.

## $ verilog
```
module HelloWorld;

initial begin
    $display("Hello World!");
    $finish;
end

endmodule
```
- Verilog, a hardware description language (HDL), was developed in the early 1980s by Phil Moorby and Prabhu Goel.

## $ COOL (Classroom Object-Oriented Language)
```
class Main {
    main(): Object {
        out_string("Hello World!\n");
        return new Int(0);
    };
};
```
- COOL was developed in the mid-1990s by a team led by Alex Aiken at Stanford University for use in education.

## $ scheme
```
(display "Hello World!")
(newline)
```
- Scheme, a dialect of Lisp, was developed in the 1970s by Gerald Jay Sussman and Guy L. Steele Jr.

## $ logo
```
print [Hello World!]
```
- Logo, a programming language primarily used for educational purposes, was developed in the late 1960s by Wally Feurzeig, Seymour Papert, and Cynthia Solomon.

## $ scratch
```
1/ Open Scratch.
2/ Drag a "When Green Flag Clicked" block from the Events category to the Scripts area.
3/ Drag a "Say Hello!" block from the Looks category and place it below the "When Green Flag Clicked" block.
4/ Customize the text inside the "Say Hello!" block to "Hello World!".
```
- Scratch was developed in the early 2000s by the Lifelong Kindergarten Group at the MIT Media Lab.

## $ eiffel
```
class
    HELLO_WORLD

create
    make

feature {NONE} -- Initialization

    make
        do
            print ("Hello World!")
        end

end
```
- Eiffel, an object-oriented programming language, was developed in the mid-1980s by Bertrand Meyer.

## $ AWK
```
BEGIN {
    print "Hello World!"
}
```
- AWK, a versatile programming language, was developed in the 1970s by Alfred Aho, Peter Weinberger, and Brian Kernighan.

## $ ABC
```
"Hello, World!"
```
- ABC is a high-level programming language designed for beginners. ABC was developed in the late 1970s by a team led by Guido van Rossum at the Centrum Wiskunde & Informatica (CWI) in the Netherlands. It served as an inspiration for the development of Python.

## $ elixir
```
IO.puts "Hello World!"
```
- Elixir, a functional, concurrent programming language, was developed by José Valim and first released in 2011.

## $ nim
```
echo "Hello World!"
```
- Nim is a statically typed, imperative programming language that supports metaprogramming. It was developed by Andreas Rumpf and first released in 2008.

## $ Limbo
```
implement Main;

sys: Sys;

Main: module {
  init: fn(nil: ref Draw->Context, argv: list of string);
};

init(nil: ref Draw->Context, argv: list of string) {
  sys = load Sys Sys->PATH;
  sys->print("Hello World!\n");
}
```
- Limbo is a programming language designed for developing distributed systems. Developed by Vita Nuova Holdings as part of the Inferno operating system project, Limbo is notable for its simplicity and its use of channels for communication between processes

## $ nermele
```
System.Console.WriteLine("Hello World!");
```
- Nemerle was first released in 2003 by a team led by Kamil Skalski at the University of Wrocław in Poland.

## $ PostScript
```
/Helvetica findfont
12 scalefont
setfont
100 100 moveto
(Hello World!) show
```
- PostScript was developed by Adobe Systems and first released in 1982.

## $ ZPL
```
^XA
^FO50,50
^A0N,50,50
^FDHello, World!^FS
^XZ
```
- ZPL was developed by Zebra Technologies and first released in the 1980s.

## $ X10
```
public class HelloWorld {
    public static def main(argv:Rail[String]) {
        Console.OUT.println("Hello World!");
    }
}
```
- X10 is designed to support high-performance computing on large-scale distributed systems and parallel architectures. It was first released in the early 2000s.

## $ pike
```
int main() {
    write("Hello, World!\n");
    return 0;
}
```
- Pike was created by Fredrik Hübinette, Roxen Internet Software, and others. It was first released in 1994.

## $ MQL4
```
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart()
  {
   //--- display "Hello, World!" in the Experts tab
   Print("Hello World!");
  }
```
- This MQL4 script simply prints "Hello World!" in the Experts tab of the MetaTrader 4 platform. MQL4 was developed by MetaQuotes Software Corp. and first released along with MetaTrader 4 in 2005.

## $ bliss
```
PROGRAM HELLO_WORLD;
BEGIN
    WRITE("Hello, World!");
END.
```
- Bliss was developed by W.A. Wulf and his colleagues at Carnegie Mellon University in the 1970s. It was widely used in academic and research settings for parallel computing applications.

## $ Go (Golang)
```
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
- Go, also known as Golang, is a statically typed, compiled programming language designed by Google. It was first released in 2009.

# Bonus

### $ BrainF*ck
```
>+++++++++[<++++++++>-]<.>+++++++[<++++>-]<+.+++++++..+++.>>>++++++++[<++++>-]
<.>>>++++++++++[<+++++++++>-]<---.<<<<.+++.------.--------.>>+.>++++++++++.
```
- It's quite cryptic, but that's the charm of Brainf*ck! It was created by Urban Müller in 1993.

## $ HTML
- NOT A PROGRAMMING LANGUAGE BUT -
```
<h1>Hello World</h1>
```

## $ Bhai Lang (Hindi Toy Programming Language)
```
hi bhai
 bol bhai "Hello World";
 
  bhai ye hai a = 3;
  bhai ye hai b = 0;

  jab tak bhai (b < 5) {
    bol bhai b;

    agar bhai (b == a) {
      bol bhai "b is equal to a";
    } nahi to bhai (b == 0) {
      bol bhai "b is equal to zero";
    }

    b += 1;
  }

bye bhai
```

## $ Mama Lang ( Bangla Toy Programming Language)
```
bol toh mama ("Hello World");
```

## $ English
```
Hello World!
```

---