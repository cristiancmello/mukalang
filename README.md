# mukalang
The Muka Language.

[Brazilian Portuguese version]()

## Purpose

Provide a theoretical and practical material for Language Engineering. For the time being I based on
Kaleidoscope language.

## Paradigm

Procedural...

## Requirements

- Knowledge in C++ and LLVM

## Roadmap (Execution based on Compiler/Transpiler)

### 0. Designing the Language [PHASE 'DESIGNING']

...

### 1. Building Lexers [PHASE 'ANALYSIS']

#### In C++ using standard library only

...generating a C++ scanner/lexer...

#### Modern Style Using ANTLR

...generating a C++ scanner/lexer...

#### Old style Using (f)lex, Yacc and Bison

...in C++...

### 2. Implementing a Parser and AST [PHASE 'ANALYSIS']

#### In C++ using standard library only

...generating a C++ parser...

#### Modern Style Using ANTLR

...generating a C++ parser...

### 3. Code Generation to LLVM IR [PHASE 'SYNTHESIS']

...

### 4. Adding JIT and Optimizer Support [PHASE 'SYNTHESIS WITH OPTIMIZATION']

...

#### 5. Extending the Language: Control Flow [PHASES 'ANALYSIS AND SYNTHESIS']

...

#### 6. Extending the Language: User-defined Operators [PHASES 'ANALYSIS AND SYNTHESIS']

...

#### 7. Extending the Language: Mutable Variables [PHASES 'ANALYSIS AND SYNTHESIS']

...

#### 8. Compiling to Object Files [PHASE 'SYNTHESIS']

...

#### 9. Debug Information [PHASE 'DEBUGGING']

...

#### 10. Adding garbage collection support, exceptions, debugging, support for "spaghetti stacks"

...

## Roadmap (Execution based on Interpreter)

...

## Future

- Implementing popular resources: package manager and community share (e.g. NPM, publishing on the Web, ...); 

## Refs

1. [Kaleidoscope: Implementing a Language with LLVM](https://llvm.org/docs/tutorial/index.html)
2. [Strumenta - Parsing Tools](https://tomassetti.me/resources-create-programming-languages/#parsing-tools)
3. [Programming Paradigms for
Dummies: What Every
Programmer Should Know - Van Roy](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf)
4. [An introduction to language lexing and parsing with ANTLR - Tahir](https://willowtreeapps.com/ideas/an-introduction-to-language-lexing-and-parsing-with-antlr)
5. [Part 01: Tutorial on lex/yacc - Engelsma](https://www.youtube.com/watch?v=54bo1qaHAfk)
6. [Why you should not use (f)lex, yacc and bison - Tomassetti](https://tomassetti.me/why-you-should-not-use-flex-yacc-and-bison/)
7. [Getting Started with ANTLR in C++ - Tomassetti](https://tomassetti.me/getting-started-antlr-cpp/)
