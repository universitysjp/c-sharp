---
title: "C# Console Applications"
---

# C# Console Applications

Structured, scenario-based console samples aligned with theory in `../Intro`.

## Index
| # | Folder | Topic | Summary |
|---|--------|-------|---------|
| 01 | [01_BasicIO](./console-basic-io) | Basic IO & Variables | Read/write console, validation |
| 02 | [02_ControlFlow](./console-control-flow) | Control Flow | if, switch, loops, break/continue |
| 03 | [03_Strings](./console-strings) | Strings | Common APIs & immutability |
| 04 | [04_Arrays](./console-arrays) | Arrays | 1D & 2D arrays, sorting |
| 05 | [05_Methods](./console-methods) | Methods | Signatures, overloading, Math, Random |
| 06 | [06_OOP](./console-oop) | OOP Basics | Classes, inheritance, polymorphism |
| 07 | [07_Exceptions](./console-exceptions) | Exceptions | try/catch/finally, custom exception |
| 08 | [08_InMemoryCRUD](./console-in-memory-crud) | CRUD | In-memory repository pattern |

## How to Run (macOS / Linux / Windows with .NET SDK)
1. Navigate into a folder (e.g. `01_BasicIO`).
2. If you convert to a project later, use `dotnet new console` and move `Program.cs` in.
3. For single-file quick run (C# 9+ script style not used here), compile:

```
csc Program.cs && mono Program.exe
```

(Or create a proper SDK project for modern workflow.)

## Linking Theory
See Intro docs:
- [Intro](./visual-programming-introduction)
- [Control Statements](./control-statements)
- [Strings](./strings)
- [Arrays](./arrays)
- [Methods](./methods)
- [OOP](./oop)