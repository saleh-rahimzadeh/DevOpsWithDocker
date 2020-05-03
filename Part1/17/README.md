# Readme
It's an image to use as a ready environment for the [Rust](https://www.rust-lang.org/) programming language.


## What is Rust?
A language empowering everyone to build reliable and efficient software. 

**Performance**  
Rust is blazingly fast and memory-efficient: with no runtime or garbage collector, it can power performance-critical services, run on embedded devices, and easily integrate with other languages. 

**Reliability**  
Rust’s rich type system and ownership model guarantee memory-safety and thread-safety — enabling you to eliminate many classes of bugs at compile-time. 

**Productivity**  
Rust has great documentation, a friendly compiler with useful error messages, and top-notch tooling — an integrated package manager and build tool, smart multi-editor support with auto-completion and type inspections, an auto-formatter, and more. 


## How to use this image
Start a Rust instance:
```bash
$ docker run --name rust -it salehz/rust
```

This image is based on Alpine linux.

Installed packages:
- rust package
- rust stable toolchains
- rust default profile
