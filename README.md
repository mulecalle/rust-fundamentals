# Rust Fundamentals

Rust is a `Static` and `Strong` language

#### Data types
- Static - We know all of the data types at compile time
- Dynamic - We only know the data types at run time

#### Enforcements
- Strong - Enforces rules on data type assignments
- Weak - Has Few or no enforcement on data type assignments

#### Language
- Compiled, fast
- Interpreted, on the fly - portable

#### Memory
- Stack - pila, last in last out, when stack overflow happens, to many data -> we use the heap
- Heap - has a pointer pointing to the data in memory 

![](./png/stack-heap.png)

## Notes

- Cannot change the value of a variable - or declare the variable as mutable.
- `Ownership and Burrowing`, Core rust memory management
- `Associated methods`, method associated to a data structure
- `Crates`, modules
- `Macros`, ! built-in functions 

## Rust Toolchain

Toolchain components:

- Rust Compilet
- Cargo (package manager)

[Rustup](https://rustup.rs/), a toolchain management utility

## Bynary command

```
> rustc
```
