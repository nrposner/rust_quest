

# Stages:

## Stage 1: The Basics

A basic introduction to essential keywords and concepts, primitive data types, and syntax. Gradually builds from the introduction of `let` to rebuilding some of the simpler elements of the standard library for personal use. This all occurs in a `no_std` environment.

Keywords/types and their rough order of introduction: 
Fundamentals: `let`, `mut`, `true`/`false`, `if`/`else`, `for`/`in`, `&`/`*`, `Option`, `Result`, 

Control Flow: `match`, `loop`, `while`, `break`, `continue`,

Functions: `fn`, `return`, `impl`,  `self`/`Self`

Types: `enum`, `struct`, 

Concepts: Declarations, Mutability, Borrowing, Scalar and Compound Types, Functions and Methods, 

## Stage 2: Exploring the Ecosystem

After gaining unfettered access to the standard library, the student is challenged to make effective use of these tools in a variety of situations, including tests which require beating certain thresholds of time and memory complexity. A focus on algorithms and memory.

Modifiers: `as`, `move` `ref`

Types: `const`, `static`, `type`, `trait`, `unsafe`, 

Crates: `serde`, `rayon` `thiserror`/`anyhow`(?),

Concepts: Memory, Error Handling, Collections, Iterators and Closures, Generics, Lifetimes, Concurrency

## Stage 3: 

The student is challenged to bring all they have learned together and construct their own crate with a single purpose: to query an external server (somehow involving concurrency) and decrypt target information using a private key.

Organization: `pub`,  `mod`, `use`, `super`, `crate`, `extern`,

Concepts: Code Organization, Testing, Smart Pointers,



